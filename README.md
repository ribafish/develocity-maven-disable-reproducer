## Develocity enable/disable sample for Maven

This project demonstrates a setup of Maven Develocity that enables and disables the plugin based on an environment variable. 

The setup can be seen in the `.mvn/develocity.xml` file, [line 7](.mvn/develocity.xml#L7). 

There are also different run scenarios showcased in github actions:
- [Run with Develocity enabled via env var](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883068734)
- [Run with Develocity explicityl disabled via env var](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883069090)
- [Run with Develocity enabled via a cmdline argument](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883069728)
- [Run with Develocity enabled via env var and overriden via cmdline argument](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883070074)
- [Run with no env var, but with access key set up](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883070347)
- [Run with Develocity enabled, but with missing access key](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883069387)
- [Run with no env var, nor access key (Develocity disabled - mimicking local developer with no additional setup)](https://github.com/ribafish/develocity-maven-disable-reproducer/actions/runs/9398205963/job/25883070669)
