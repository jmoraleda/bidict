.. Forward declarations for all the custom interpreted text roles that
   Sphinx defines and that are used below. This helps Sphinx-unaware tools
   (e.g. rst2html, PyPI's and GitHub's renderers, etc.).
.. role:: doc

.. Use :doc: rather than :ref: references below for better interop as well.


bidict
======

*The bidirectional mapping library for Python.*


Status
------

.. image:: https://img.shields.io/pypi/v/bidict.svg
   :target: https://pypi.org/project/bidict
   :alt: Latest release

.. image:: https://img.shields.io/readthedocs/bidict/main.svg
   :target: https://bidict.readthedocs.io/en/main/
   :alt: Documentation

.. image:: https://github.com/jab/bidict/workflows/Tests/badge.svg
   :target: https://github.com/jab/bidict/actions
   :alt: GitHub Actions CI status

.. image:: https://img.shields.io/pypi/l/bidict.svg
   :target: https://raw.githubusercontent.com/jab/bidict/main/LICENSE
   :alt: License

.. image:: https://static.pepy.tech/badge/bidict
   :target: https://pepy.tech/project/bidict
   :alt: PyPI Downloads

.. image:: https://img.shields.io/github/sponsors/jab
   :target: https://github.com/sponsors/jab
   :alt: Sponsors on GitHub

.. image:: https://img.shields.io/badge/GitHub-sponsor-ff69b4
   :target: https://github.com/sponsors/jab
   :alt: Sponsor on GitHub


Features
--------

- Depended on by
  Google, Venmo, CERN, Baidu, Tencent,
  and teams across the world since 2009

- Familiar, Pythonic APIs
  that are carefully designed for
  safety, simplicity, flexibility, and ergonomics

- Lightweight, with no runtime dependencies
  outside Python's standard library

- Implemented in
  concise, well-factored, fully type-hinted Python code
  that is optimized for running efficiently
  as well as for long-term maintenance and stability
  (not to mention `joy <#learning-from-bidict>`__ :)

- Extensively `documented <https://bidict.readthedocs.io>`__

- 100% test coverage
  running continuously across all supported Python versions


Installation
------------

``pip install bidict``


Quick Start
-----------

.. code:: python

   >>> from bidict import bidict
   >>> element_by_symbol = bidict({'H': 'hydrogen'})
   >>> element_by_symbol['H']
   'hydrogen'
   >>> element_by_symbol.inverse['hydrogen']
   'H'


For more usage documentation,
head to the :doc:`intro` [#fn-intro]_
and proceed from there.


Enterprise Support
------------------

Enterprise-level support for bidict can be obtained via the
`Tidelift subscription <https://tidelift.com/subscription/pkg/pypi-bidict?utm_source=pypi-bidict&utm_medium=referral&utm_campaign=readme>`__
or by `contacting me directly <mailto:jabronson@gmail.com>`__.

I have a US-based LLC set up for invoicing,
and I have 15+ years of professional experience
delivering software and support to companies successfully.

You can also sponsor my work through platforms like GitHub Sponsors.
See the `Sponsoring <#sponsoring>`__ section below for details,
including rationale and examples of companies
supporting the open source projects they depend on.


Voluntary Community Support
---------------------------

Please search through already-asked questions and answers
in `GitHub Discussions <https://github.com/jab/bidict/discussions>`__
and the `issue tracker <https://github.com/jab/bidict/issues?q=is%3Aissue>`__
in case your question has already been addressed.

Otherwise, please feel free to
`start a new discussion <https://github.com/jab/bidict/discussions>`__
or `create a new issue <https://github.com/jab/bidict/issues/new>`__ on GitHub,
or ask in the `bidict chatroom <https://gitter.im/jab/bidict>`__
for voluntary community support.


Notice of Usage
---------------

If you use bidict,
and especially if your usage or your organization is significant in some way,
please let me know in any of the following ways:

- `star bidict on GitHub <https://github.com/jab/bidict>`__
- post in `GitHub Discussions <https://github.com/jab/bidict/discussions>`__
- leave a message in the `chat room <https://gitter.im/jab/bidict>`__
- `email me <mailto:jabronson@gmail.com>`__


Changelog
---------

For bidict release notes, see the :doc:`changelog`. [#fn-changelog]_


Release Notifications
---------------------

.. duplicated in CHANGELOG.rst:
   (would use `.. include::` but GitHub doesn't understand it)

Watch `bidict releases on GitHub <https://github.com/jab/bidict/releases>`__
to be notified when new versions of bidict are published.
Click the "Watch" dropdown, choose "Custom", and then choose "Releases".


Learning from bidict
--------------------

One of the best things about bidict
is that it touches a surprising number of
interesting Python corners,
especially given its small size and scope.

Check out :doc:`learning-from-bidict` [#fn-learning]_
if you're interested in learning more.


Contributing
------------

I have been bidict's sole maintainer
and `active contributor <https://github.com/jab/bidict/graphs/contributors>`__
since I started the project ~15 years ago.

Your help would be most welcome!
See the :doc:`contributors-guide` [#fn-contributing]_
for more information.


Sponsoring
----------

.. duplicated in CONTRIBUTING.rst
   (would use `.. include::` but GitHub doesn't understand it)

.. image:: https://img.shields.io/badge/GitHub-sponsor-ff69b4
  :target: https://github.com/sponsors/jab
  :alt: Sponsor through GitHub

.. image:: https://img.shields.io/github/sponsors/jab
   :target: https://github.com/sponsors/jab
   :alt: Sponsors on GitHub

Bidict is the product of thousands of hours of my unpaid work
over the ~15 years that I've been the sole maintainer.

If bidict has helped you or your company accomplish your work,
please `sponsor my work through GitHub <https://github.com/sponsors/jab>`__
and/or ask your company to do the same.

Choose a tier and GitHub handles everything else.
Your GitHub sponsorship will automatically go
on the same bill you already have set up with GitHub,
so after the one-click signup, there's nothing else to do.

See the following for rationale and examples of companies
supporting the open source projects they depend on
in this manner:

- `<https://engineering.indeedblog.com/blog/2019/07/foss-fund-six-months-in/>`__
- `<https://engineering.atspotify.com/2022/04/announcing-the-spotify-foss-fund/>`__
- `<https://blog.sentry.io/2021/10/21/we-just-gave-154-999-dollars-and-89-cents-to-open-source-maintainers>`__

.. - `<https://www.onepercent.dev>`__
.. - `<https://sethmlarson.dev/blog/people-in-your-software-supply-chain>`__
.. - `<https://www.cognitect.com/blog/supporting-open-source-developers>`__
.. - `<https://vorpus.org/blog/the-unreasonable-effectiveness-of-investment-in-open-source-infrastructure/>`__

You can also support my work through
`Gumroad <https://gumroad.com/l/bidict>`__ or
`PayPal <https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=jabronson%40gmail%2ecom&lc=US&item_name=Sponsor%20bidict>`__,
or through a support engagement with my LLC.
See `Enterprise Support <#enterprise-support>`__
above for details.


Finding Documentation
---------------------

If you're viewing this on `<https://bidict.readthedocs.io>`__,
note that multiple versions of the documentation are available,
and you can choose a different version using the popup menu at the bottom-right.
Please make sure you're viewing the version of the documentation
that corresponds to the version of bidict you'd like to use.

If you're viewing this on GitHub, PyPI, or some other place
that can't render and link this documentation properly
and are seeing broken links,
try these alternate links instead:

.. [#fn-intro] `<https://bidict.readthedocs.io/intro.html>`__ | `<docs/intro.rst>`__

.. [#fn-changelog] `<https://bidict.readthedocs.io/changelog.html>`__ | `<CHANGELOG.rst>`__

.. [#fn-learning] `<https://bidict.readthedocs.io/learning-from-bidict.html>`__ | `<docs/learning-from-bidict.rst>`__

.. [#fn-contributing] `<https://bidict.readthedocs.io/contributors-guide.html>`__ | `<CONTRIBUTING.rst>`__


.. image:: https://static.scarf.sh/a.png?x-pxid=05e3c4e4-eaa7-41a1-84c2-ec14413115f8
