# presentation-template
A barebones [reveal.js](https://github.com/hakimel/reveal.js/) deck for Deis presentations.

## Setting up

To get started, fork this repository and name it for your talk. Then, clone it
and initialize submodules:

- Clone with `--recursive`:
```
git clone ${REPO_URL} --recursive
```
OR
- Clone normally and then initialize submodules:
```
git clone ${REPO_URL}
git submodule update --init --recursive
```

## Editing

Opening `index.html` in your browser should render the presentation. Make
changes to the HTML and reload.

The document has HTML comments around blocks you'll likely want to customize.

## Presenting

Push to the `gh-pages` branch of your fork and GitHub Pages should start rendering your static presentation at your repository URL. For example: http://carmstrong.github.io/ceph-days-sf-deis-2015/

## Past Talks

This template has been the basis for several talks:

* [Lessons Learned From Building Platforms on Top of CoreOS](http://gabrtv.github.io/10-lessons-learned-using-coreos/) at [CoreOS Fest 2015](https://www.youtube.com/watch?list=PLlh6TqkU8kg8Ld0Zu1aRWATiqBkxseZ9g&v=yCWhnLlFvhI) by [@gabrtv](https://github.com/gabrtv)
* [Containerized Ceph and Deis](http://carmstrong.github.io/ceph-days-sf-deis-2015/) at [Ceph Day SF 2015](http://ceph.com/cephdays/ceph-day-san-francisco/) by [@carmstrong](https://github.com/carmstrong)
* [Transitioning to Container-based Infrastructure](http://gabrtv.github.io/costanoa-containers-2014/) at Costanoa VC Day by [@gabrtv](https://github.com/gabrtv)
* [Deis + Mesos: Docker PaaS at Scale](http://gabrtv.github.io/deis-qconsf-2014/) at [QCon SF 2014](https://qconsf.com/sf2014/index.html) by [@gabrtv](https://github.com/gabrtv)
* [Evolution of a Docker PaaS](http://gabrtv.github.io/deis-dockercon-2014/) at [DockerCon 2014](https://www.youtube.com/watch?v=GnIsmNN1sVA&list=PLkA60AVN3hh_CglPdPy3M_4yv_XEmXE10&index=17) by [@gabrtv](https://github.com/gabrtv)
