0.1.7 (2019-04-11 12:45:00 -0800)
---------------------------------
* Use keyword arguments only for protocol_class invocations (`#52 <https://github.com/osrf/osrf_pycommon/issues/52>`_)
* Contributors: Daniel Stonier

0.1.6 (2018-11-15 12:45:00 -0800)
---------------------------------
- Changed package.xml to use python2 or python3 dependencies as appropriate. `#50 <https://github.com/osrf/osrf_pycommon/pull/50>`_

0.1.5 (2018-06-19 21:00:00 -0800)
---------------------------------
- Fixed a try-catch statement to adapt to changes in asyncio's raise behavior in `asyncio.get_event_loop()`.
- Small changes, mostly related to distribution.

0.1.4 (2017-12-08 16:00:00 -0800)
---------------------------------
- Only small test/linter fixes and documentation typos removed.

0.1.3 (2017-03-28 19:30:00 -0800)
---------------------------------
- Fix to support optional arguments in verb pattern `#24 <https://github.com/osrf/osrf_pycommon/pull/24>`_


0.1.2 (2016-03-28 19:30:00 -0800)
---------------------------------
- Started keeping a changelog.
- Changed ``process_utils`` module so that it will use Trollius even on Python >= 3.4 if ``trollius`` has previously been imported.
