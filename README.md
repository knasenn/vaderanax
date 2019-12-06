Anax WEATHER mod (v1)
==================================




Install as Anax module
------------------------------------

This is how you install the module into an existing Anax installation.

Install using composer.

```
composer require aiur18/ipvader "dev-master"
```

Copy the needed files, configuration and setup the weathermod

```
rsync -av vendor/aiur18/ipvader/.anax/ .anax/
rsync -av vendor/aiur18/ipvader/config/ config/
rsync -av vendor/aiur18/ipvader/src/ src/
rsync -av vendor/aiur18/ipvader/test/ test/
rsync -av vendor/aiur18/ipvader/view/ view/
rsync -av vendor/aiur18/ipvader/.phpcs.xml ./
rsync -av vendor/aiur18/ipvader/.phpdoc.xml ./
rsync -av vendor/aiur18/ipvader/.phpmd.xml ./
rsync -av vendor/aiur18/ipvader/.phpunit.xml ./
rsync -av vendor/aiur18/ipvader/LICENSE.txt ./
rsync -av vendor/aiur18/ipvader/README.md ./
rsync -av vendor/aiur18/ipvader/REVISION.md ./

```


Dependency
------------------

This is a Anax modulen and primarly intended to be used together with the Anax framework.
Run the following script.
```
./.anax/scaffold/postprocess.bash
```


License
------------------

This software carries a MIT license. See LICENSE.txt for details.



```
 .  
..:  Copyright (c) 2017 - 2019 knasenn (knasenn@dbwebb.se)
```
