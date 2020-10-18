commit a8ae7df6f94f0e25513f749e1c5b1573ee2fa8b1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 21:46:47 2020 -0400

    Removed Debian/RedHat specific tasks
    
    - Consolidating installs

commit 26c5e4f30efb32bfca67299b9ec40d1a0467ee9e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 20:08:38 2020 -0400

    Adding sudo package for all distros
    
    To ensure sudo is installed for all tested distros

commit 413a999eadff2564cb38e30106e44696c6b5c5b7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 18:47:58 2020 -0400

    Molecule changes required to properly test
    
    Because of new changes added in latest Molecule version, some changes needed to be made

commit 7e53a7c020429c1fe7f43f98d0c134d429cd9aa0
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 18:46:31 2020 -0400

    Updated versions of tools and added new products
    
    Now includes Boundary and Waypoint

commit 056eaaf40746a86d2bc5b96bee651181be78d9f6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 18:46:01 2020 -0400

    Added Python bootstrap role
    
    - Need to ensure that Python role is applied

commit 3ba8d21739fd3e10713209dffe2a5eef1e099b43
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 18:03:13 2020 -0400

    Added Molecule Docker as it is now independent

commit c4a6ee20faff629065e33e6b0112e10f2ea5634c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 18:02:42 2020 -0400

    Fixing issue with building Docker images
    
    https://github.com/ansible-community/molecule/issues/2891

commit 95c48b26a7b5f003b91d1486c23a34ba82880d79
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 10:35:22 2020 -0400

    Added linting tool configs

commit 403a530fd58bfaae9bf981f158adb576ca57e53b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 10:35:02 2020 -0400

    Updated example playbook

commit 1168d30f72f07f146d465603d378b654efe761a9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 10:34:41 2020 -0400

    Updated CI pipeline tests

commit c6025d45dac512e997f8ab7616ae614942a30531
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 10:34:11 2020 -0400

    Updated Python requirements

commit 4eefa8b4737aae03e5f7586c7d6e9aa83093a85b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Oct 16 10:33:34 2020 -0400

    Updated Molecule tests

commit ee7d367576e6001121c0eba5059e5596e89ef3a7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 16:24:40 2020 -0500

    Changed Molecule scenarios, tests, etc.

commit 75856ae5c1c3df2498447097ede36fa2fde586e3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 16:24:28 2020 -0500

    Updated files, etc. after new structure

commit 44bae4dc895f51ff1e0b73926d323f411839685f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 12:59:46 2020 -0500

    New files, etc. added based on cookiecutter template

commit 25bbb6e5742f36da81fbc49f2897be2ef141229b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 12:59:30 2020 -0500

    Files removed based on cookiecutter template

commit 58e3292022c8bd4a7b49d74d85b5caedd5bc24c1
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Feb 19 12:59:02 2020 -0500

    Changes implemented based on cookiecutter template

commit 443897fefa6dfe61840453b178ecabc6bb14326f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Nov 18 01:12:53 2019 -0500

    Refactored role
    
    - Removed old Vagrant testing
    - Added Molecule testing
    - Updated Travis CI testing to use Molecule
    - Cleaned up code
      - Cleaned up conditionals
      - Changed with_items to loop

commit 326cec99b3b519a56c34ea512a3db95391f8dbf4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Mar 17 01:24:32 2019 -0400

    Cleaned up formatting

commit f18df11c7015f2ef6b8712dfbab71756d07c585a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Mar 17 01:24:24 2019 -0400

    Added missing unzip pre-req

commit 3c9e65625328f5d988bed81935ccadbb459102b7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Sep 19 17:47:43 2018 -0400

    Added RedHat support for Vagrant

commit fae2687e64f2ba8cc5ce1ec912572c8797f9da28
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Jul 8 15:22:06 2018 -0400

    New installation logic

commit 72298ba111433a990d0cd0ab46c0badf02963462
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Mar 18 20:25:44 2018 -0400

    Updated versions, cleaned up code, prepping for further refactoring

commit c6d394c09a2dcbde75719ff7ee551dd549dec7a2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 12:24:08 2017 -0400

    Fixed syntax issue
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit f4be92b1c7f3a90bb767292c08d8149982a7f9e4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 12:11:58 2017 -0400

    Added conditional for executing in check mode
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7977194e69f7cb7de571b244a3c2cc901f7253f7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 12:07:56 2017 -0400

    Fixed syntax issue
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6eb1b3d87637e5e098fcfac0ecc184a8534936db
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 12:04:27 2017 -0400

    Added Travis build status
    badge
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 05c480e684e3c3e68cefb1016d98e41b128f78a6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Apr 20 12:02:42 2017 -0400

    Cleaned up code, updated to latest versions and added Travis testing
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit faf3886737069b692712cddb8dd283013e5f2b5c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Tue Aug 30 01:33:18 2016 -0400

    Updated versions
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit e37b16d9503f822b8288238beceee8a6a3bc4f21
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Wed Jul 6 00:29:15 2016 -0400

    Updated versions
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 271a077e7c9bd7923d5add74769e8934c76e895d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Mon Feb 29 22:45:41 2016 -0500

    Updated versions
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit 3058f6a98a181b25a18ad968ea1ec4abc01e6f0d
Author: Larry Smith Jr <mrlesmithjr@gmail.coml>
Date:   Fri Jan 22 22:59:15 2016 -0500

    Added Galaxy info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.coml>

commit d80c00e30256910216bc237011b73af1dd3badca
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Jan 10 00:32:21 2016 -0500

    Fixed incorrect play name
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 49241e3f45bf56928fea13bd2fded08936e3741f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 20:07:10 2016 -0500

    Added serf and consul
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 6ff0ff05881845c2a610145ebd2d9187cf4ca65f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 20:01:54 2016 -0500

    Added Vagrant info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 2b0153faa2646f130fa6f78ccc618e11802ce2e7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 19:55:56 2016 -0500

    Updated Vagrant build
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 8f270dc8703dd5e74b01b1893df08ead001b516a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 19:53:17 2016 -0500

    Added Vagrant build info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit f3006d44456ead51b0aa3b66308eb69e922cb8a5
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 19:53:03 2016 -0500

    Added info about role
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit f30944ad4ed05a09eaab44a686f1db25757c596e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 19:34:25 2016 -0500

    Fixed wrong download for i386
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit b461521dd2de789931cef441e39ca12cae1c1d90
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Jan 9 19:31:45 2016 -0500

    first commit
