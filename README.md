# netology-home-2.4
1.	commit aefead2207ef7e2aa5dc81a34aedf0cad4c32545
Author: Alisdair McDiarmid <alisdair@users.noreply.github.com>
Date:   Thu Jun 18 10:29:58 2020 -0400

    Update CHANGELOG.md

2.	85024d310 (HEAD, tag: v0.12.23) v0.12.23
3.	commit 9ea88f22fc6269854151c571162c5bcf958bee2b
	Author: Chris Griggs <cgriggs@hashicorp.com>
	Date:   Tue Jan 21 17:08:06 2020 -0800

   	 add/update community provider listings

	commit 56cd7859e05c36c06b56d013b55a252d0bb7e158 (HEAD)
	Merge: 58dcac4b7 ffbcf5581
	Author: Chris Griggs <cgriggs@hashicorp.com>
	Date:   Mon Jan 13 13:19:09 2020 -0800

    	Merge pull request #23857 from hashicorp/cgriggs01-stable
    
    	[cherry-pick]add checkpoint links
	
4.
33ff1c03b (tag: v0.12.24) v0.12.24
b14b74c49 [Website] vmc provider links
3f235065b Update CHANGELOG.md
6ae64e247 registry: Fix panic when server is unreachable
5c619ca1b website: Remove links to the getting started guide's old location
06275647e Update CHANGELOG.md
d5f9411f5 command: Fix bug when using terraform login on Windows
4b6d06cc5 Update CHANGELOG.md
dd01a3507 Update CHANGELOG.md	
225466bc3 Cleanup after v0.12.23 release
85024d3100126de36331c6982bfaac02cdab9e76 (tag: v0.12.23)

5.
commit 8c928e83589d90a031f811fae52a81be7153e82f
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Thu Apr 2 18:04:39 2020 -0700

6.
commit 52dbf94834cb970b510f2fba853a5b49ad9b1a46
Author: James Bardin <j.bardin@gmail.com>
Date:   Wed Aug 9 17:46:49 2017 -0400

    keep .terraform.d/plugins for discovery
   
commit 41ab0aef7a0fe030e84018973a64135b11abcd70
Author: James Bardin <j.bardin@gmail.com>
Date:   Wed Aug 9 10:34:11 2017 -0400

    Add missing OS_ARCH dir to global plugin paths
    
commit 66ebff90cdfaa6938f26f908c7ebad8d547fea17
Author: James Bardin <j.bardin@gmail.com>
Date:   Wed May 3 22:24:51 2017 -0400

    move some more plugin search path logic to command
    
    Make less to change when we remove the old search path

commit 8364383c359a6b738a436d1b7745ccdce178df47
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Thu Apr 13 18:05:58 2017 -0700

    Push plugin discovery down into command package

7. 
commit 5ac311e2a91e381e2f52234668b49ba670aa0fe5
Author: Martin Atkins <mart@degeneration.co.uk>
Date:   Wed May 3 16:25:41 2017 -0700

    main: synchronize writes to VT100-faker on Windows
