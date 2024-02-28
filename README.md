## Legacy Theme Setup
- Clone repository within the `/tutor_root/env/build/openedx/themes` project directory

Type `tutor dev settheme mogc-theme` within your console

### Adding Theme within Admin Dashboard (Not Necessary)
- To access the LMS Admin go to [http://local.overhang.io:8000/admin/](http://local.overhang.io:8000/admin/) within your chosen browser
- Navigate to *Site Themes* section and select **Add Site Theme**
- Select **http://local.overhang.io:8000/admin/** in the *Site* dropdown field
- Type **mogc-theme** in the *Theme dir name* field
- Select **Save**

Stop/Restart `dev` server using `tutor dev stop` and `tutor dev start -d` respectively

Theme will be available on local at [http://local.overhand.io:8000/dashboard/](http://local.overhand.io:8000/dashboard/)

### Helpful Links
- Tutor Documentation: [https://docs.tutor.edly.io/tutorials/theming.html](https://docs.tutor.edly.io/tutorials/theming.html)
