Arjun 2.0 - offline SLI capture (iPad install, no server app needed)

1. Put this folder on any HTTPS web address once (e.g. GitHub Pages). It only serves the files;
   no data is ever sent there.
2. On the iPad, open that address in Safari, tap Share > Add to Home Screen.
3. Open Arjun from the Home Screen icon once while online. From then on it runs fully offline
   from the icon, with nothing else running.

Data stays on the device. The Home Screen copy has its own storage, separate from Safari or
HTML Serve, so export anything you need from the old setup first.
To update: change index.html, bump VERSION in sw.js, re-upload, open the app once online.
