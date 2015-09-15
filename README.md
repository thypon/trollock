# trollock

**trollock** is PAM based X11 screen locker that hides all windows

## Features

 - PAM based
   - use any PAM module you like
   - run by regular user, no root setuid is ever required
 - Background actions
   - **blank** blank the screen, hide desktop content
   - **none** do not hide anything, as former trollock did
   - **bg** hide windows, show just root window background. This work if root
     window has one.

## Usage
Run **trollock** to lock, and type your password to unlock.

Default behaviour
```bash
trollock
trollock -p system-local-login -b blank
```

Another run
```bash
trollock -p login -b none
```

Try this!
```bash
trollock -b bg
```

### More
Project page http://aanatoly.github.io/xtrlock-pam
