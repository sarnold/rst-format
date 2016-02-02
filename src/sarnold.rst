
.. Process this file to a pdf using the command : "rst2pdf -s pdf-resume.style sarnold.rst"

==================
 Stephen L Arnold
==================

Systems Engineer/Architect and Scientist
========================================
+--------------------------------------+-----------------------+-------------------+
|:Address: USA (Santa Maria, CA)       |:Degrees:   BS/MS      |.. image:: id.jpg  |
|:Tel: +01 (805) 863-8299              |:Languages: English    |   :scale: 22%     |
|:Email: stephen.arnold42@gmail.com    |      Math             |   :align: center  |
+--------------------------------------+-----------------------+-------------------+


Education
---------
:1995-Present: Graduate/short courses in Risk Assessment, C, Ada, Zope, 
  Doppler and Polarimetric Weather Radar, 595th TEG Test and Evaluation Course,
  AMS Faculty Workshop, AHC Professional Development courses.

:1990: MS Degree in Geophysics, San Diego State University.  Thesis topic: Atmospheric
  Resonance Waves Over the Sea of Cortés: An Experimental Case Study

:1986: BS Degree in Geophysics, San Diego State University.


Technical skills
----------------
:CS/SE: Strong knowledge of programming languages and tools, system performance,
  design, testing, and administration, as well as the software lifecycle, CI,
  software processes, requirements engineering, and system architecture
:Operating Systems: Unix/Linux/Embedded (Gentoo, OE, RHEL, Debian/Ubuntu),
  Android, CyberSecurity
:Project Management: OpenAdams, SCM tools, Make/Autotools, trac, doxygen
:DataBase: SQL, Postgres/spatial, sqlite, redis/nosql
:Software: Libre/Open office tools, docutils, graphviz, Dia, Inkscape
:Embedded Systems: Gentoo, OpenEmbedded, design/deployment of applications
  for ARM and other embedded systems, Android, debian/Ubuntu


Languages
---------
:English: Native
:Spanish: Conversational(-ish)
:Math: Fluent
:Programming: Python, Ada, Bash/POSIX Shell, AWK, FORTRAN, C, Java, C++, Perl, js
:Markup: reStructuredText, HTML, DTML, XML, Markdown
:Architectures: x86/x86_64, ARM/AVR, Sparc, PowerPC, MIPS
:Engineering: IV&V, OOD/P, UML, DoDAF, 2167/498/12227, toolchains/SDKs, CI/Agile,
  jenkins/apache/trac/svn/git workflows, open document production


Business Experience
-------------------

:2014 - Present: Startup Mentor and Tech Adviser - Technology and Open Source
  adviser, `Santa Maria Startup Weekend`_ and local startup meetups.  Open source
  presentations, technology training, demos.

:2014 - Present: Principal Scientist, Systems Architect, Business Development -
  `VCTLabs, Inc`_ - Goleta, CA.  VCT Product/Project management, conferences/expos,
  open source outreach & education. Launch Range Systems Subject Matter Expert
  (SME), education & training instructor.  Systems Architecture and CyberSecurity
  on Gentoo, OpenEmbedded, RHEL, and Debian/Ubuntu.
  Linux development/build/deployment testing.  Linux kernel/u-boot and software
  testing on various ARM devices (Gentoo Linux, OE).  Business/community
  development (event support, outreach, presentations, proposals).

.. _Santa Maria Startup Weekend: http://santamaria.startupweekend.org/
.. _VCTLabs, Inc: http://www.vctlabs.com

Open Source Experience
----------------------

:2015 - Present: Co-maintainer of imx233-olinuxino boards for the `FSL Community BSP`_
  (tested with Yocto/OpenEmbedded and meta-fsl*).

:2014 - Present: Founding member `Central Coast Open Source Solutions Exchange`_,
  an open source technology-focused meetup.

:2012 - Present: Contributing developer - OpenEmbedded_ and Yocto_.

:2003 - Present: Senior Developer - `Gentoo Linux`_.  Maintainer of developer
  tools, GIS/scientific libraries, mentor of new developers, currently primary
  maintainer of `Gentoo ARM overlay`_ and my own `dev overlay`_.

:2000 - Present: Upstream developer and/or maintainer of several tools and
  utility libraries for source code metrics, graphics, science, and education.
  See the `maintenance release page`_ and the individual github project sites
  for more information.

.. _FSL Community BSP: http://freescale.github.io/doc/release-notes/1.8/
.. _Central Coast Open Source Solutions Exchange: http://www.meetup.com/Central-Coast-Open-Source-Solutions-Exchange/
.. _OpenEmbedded: http://www.openembedded.org/
.. _Yocto: https://www.yoctoproject.org
.. _Gentoo Linux: https://www.gentoo.org/
.. _Gentoo ARM overlay: https://github.com/gentoo/arm
.. _dev overlay: https://github.com/sarnold/portage-overlay
.. _maintenance release page: http://www.gentoogeek.org

Education Experience
--------------------

:1999 - 2009: Associate Faculty - `Allan Hancock College`_ (senior geography
  and meteorology instructor). Taught Physical and Human Geography courses
  and ocassional technology courses, updated official geography course
  outlines, created new introductory meteorology course.

.. _Allan Hancock College: http://www.hancockcollege.edu

Projects
--------
  * Member of the development team of stellarium_.
  * Created a few open source video games for desktop: guisterax_,
    `helvin space trip`_.
  * Made a mobile version of stellarium for the nokia N900:
    `stellarium mobile`_. awarded the first price (25000$) in Nokia
    `calling all innovators contest`_, category "Best
    application for the Nokia N900".
  * Laoshi_: an open source Chinese learning software.
  * Chatocracy_: meet new friends and talk to them with your webcam.
  * `Super Medusa`_: video game for symbian phones.

.. _`calling all innovators contest`: http://www.callingallinnovators.com/
.. _stellarium: http://www.stellarium.org
.. _`stellarium mobile`: http://stellarium-mobile.org
.. _laoshi: http://chinese-laoshi.org
.. _guisterax: http://www.dsource.org/projects/guisterax
.. _`helvin space trip`: http://sourceforge.net/projects/helvinspacetrip
.. _chatocracy: http://www.chatocracy.com
.. _`Super Medusa`: http://www.noctua-software.com/super-medusa

Personal
--------
:Home site: http://www.gentoogeek.org
:Repositories: https://github.com/sarnold
:Papers: http://www.researchgate.net/profile/Stephen_Arnold4
:Hobbies: Guitar/Bass/Pecussion, Science Fiction, Open Source

.. raw:: pdf

   PageBreak

Appendix A
----------

Example of open source use in engineering; graphviz diagrams and IV&V.

Overall IV&V and Engineering Processes
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Revise: Problem described in AR was partially fixed but needs additional work;
  a new revision of an AR has been written.
* Validate: Developer/customer validates ARs in the Pending state.
* Prioritize: Developer/customer prioritizes ARs and assign to project(s).
* Verify: IV&V verifies ARs declared fixed by the developer.  Partial fixes
  generate a revision of the original AR (the latter is closed based on the partial fix).
* Report: IV&V reports AR State changes and status of open ARs.

AR States and Status
~~~~~~~~~~~~~~~~~~~~

* Draft State: Anomaly Reports begin in a draft status for IV&V peer review;
  refined drafts may be circulated outside IV&V if warranted.

  * Draft Status: IV&V peer review of potential anomalies results in publication
    of draft AR.

* Open State: Open ARs begin with a status of "Pending" when an approved draft
  AR is published.  Engineering review leads to the next status change, typically
  "Valid".  Valid ARs are prioritized and assigned to an appropriate project;
  when engineering considers the problem fixed, the AR status is changed to
  "Fixed".  Fixed ARs are verified by IV&V, and their status changed to 
  "Verified" if the problem was fixed.  In the case of a "partial" fix,
  a the original AR is declared "Verified" and closed based on the fix,
  and a new revision of the AR is written to describe any remaining issues.

  * Pending Status: An original or revised AR is generated, entered in the
    database, and delivered to project distribution list.
  * Valid Status: Developer (or customer) validates that AR identifies an
    error or problem condition that must be fixed.
  * Fixed Status: Problem described in AR is considered fixed by developer
    but has not been verified by IV&V.
  * Verified Status: Problem has been fixed by developer and IV&V has
    verified the fix.

* Closed state: Typically closed ARs have the status "Verified" (verified
  by IV&V), however, there are several other potential status flags for
  closed ARs, depending on the circumstances (see below).

  * Invalid Status: AR is considered technically inaccurate and does
    not describe an error.
  * Rejected Status: AR is technically accurate but the problem will
    not be fixed due to non-technical reasons.
  * Accepted Risk Status: Cost/benefit ratio does not justify fixing
    the problem.
  * Unverifiable Status: Original problem cannot be recreated in order
    to verify fix, and there is no other recourse.
  * Reconfigured Status: System has changed such that the original problem
    no longer applies.

.. raw:: pdf

   PageBreak

.. figure:: images/anomaly_state_diagram-2.svg
   :align: center
   :scale: 80%

   Anomaly Report And Tracking State Diagram

.. raw:: pdf

   PageBreak

The Dot source code for the graphviz diagram is included below.

.. include:: images/anomaly_state_diagram.dot
   :code:
   :literal:
   :number-lines:


