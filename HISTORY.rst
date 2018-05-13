

History
=======

GitHub Log
----------

* Sep 08, 2015
    - (by: sonofeft) 
        - version 0.0.15
            Tweaked history.rst
            Fixed examples subdirectory install
* Sep 06, 2015
    - (by: sonofeft) 
        - Update HISTORY.rst
        - Version 0.0.14
        - removed make_toctree from fulltoc.py
            Added some mock module logic to read_the_docs.rst
            Added some apt-get logic to travis_ci.rst
* Sep 02, 2015
    - (by: sonofeft) 
        - History update
        - Version 0.0.13
            package_data needed to be added for templates
        - History update
        - Version 0.0.10
* Aug 31, 2015
    - (by: sonofeft) 
        - Version 0.0.9
            Updated HISTORY.rst
        - Cosmetic tweak to generic_log.svg file
* Aug 30, 2015
    - (by: sonofeft) 
        - Added Generic SVG Logo
        - Updated HISTORY.rst by running history_from_github_api.py
        - Version 0.0.8
            Added copyright page to docs.
        - Version 0.0.7
            Cleaned up history.rst and authors.rst as well as quickstart template
        - Added Quickstart page to docs
            Added logo change out instructions.
            Added PyHatch links to history.rst page.
        - Version 0.0.6
            Added AUTHORS.rst, fixed history script bug, and link error
* Aug 29, 2015
    - (by: sonofeft) 
        - fixed doc error on PyHatch.cfg location
        - Added ``Making History`` page
            In sphinx docs, described how to run history_from_github_api.py python
            script.
            Also added a little doc cleanup.
* Aug 28, 2015
    - (by: sonofeft) 
        - Added HISTORY.rst generation from GitHub API
            Included all the scripts and templates to make a History page in the
            Sphinx docs.  Also added build_all_html.py in /docs/ subdirectory to
            ``touch`` all rst files such that sphinx will rebuild the whole site.
        - Update docs and tox
            Lots of tweaks to new project checklist and quickstart as well as adding
            coverage to tox.ini and tox.ini templates
* Aug 27, 2015
    - (by: sonofeft) 
        - After pylint
* Aug 26, 2015
    - (by: sonofeft) 
        - Added Example Usage, Made GUI Smaller
* Aug 25, 2015
    - (by: sonofeft) 
        - Fixed broken tox
            Moving PyHatch.cfg to user home directory and adding image shields to
            README.rst broke tox
        - added generic img shields
        - fixed "python setup.py test"
        - doc and version cleanup
* Aug 23, 2015
    - (by: sonofeft) 
        - fixed setup.py
        - first commit of existing code base
