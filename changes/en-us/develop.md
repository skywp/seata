Add changes here for all PR submitted to the develop branch.

<!-- Please add the `changes` to the following location(feature/bugfix/optimize/test) based on the type of PR -->

### feature:
- [[#5803](https://github.com/seata/seata/pull/5803)] docker image supports JVM parameter injection

### bugfix:
- [[#5749](https://github.com/seata/seata/pull/5749)] case of the pk col-name in the business sql is inconsistent with the case in the table metadata, resulting in a rollback failure
- [[#5762](https://github.com/seata/seata/pull/5762)] change some fields type of TableMetaCache to avoid integer overflow
- [[#5769](https://github.com/seata/seata/pull/5769)] fix the problem that the parameter prefix requirement of the setAttachment method in sofa-rpc is not met
- [[#5814](https://github.com/seata/seata/pull/5814)] fix XA transaction start exception and rollback failure
- [[#5771](https://github.com/seata/seata/pull/5771)] insert executor keywords unescape
- [[#5819](https://github.com/seata/seata/pull/5814)] fix oracle column alias cannot find

### optimize:
- [[#5804](https://github.com/seata/seata/pull/5804)] optimize docker default timezone
- [[#5815](https://github.com/seata/seata/pull/5815)] support the nacos application name property
- [[#5820](https://github.com/seata/seata/pull/5820)] unified log output directory
- [[#5822](https://github.com/seata/seata/pull/5822)] upgrade some deprecated github actions

### security:
- [[#5728](https://github.com/seata/seata/pull/5728)] fix some dependencies vulnerability
- [[#5766](https://github.com/seata/seata/pull/5766)] fix some serializer vulnerabilities

### test:
- [[#XXX](https://github.com/seata/seata/pull/XXX)] XXX

Thanks to these contributors for their code commits. Please report an unintended omission.

<!-- Please make sure your Github ID is in the list below -->
- [slievrly](https://github.com/slievrly)
- [capthua](https://github.com/capthua)
- [robynron](https://github.com/robynron)
- [dmego](https://github.com/dmego)
- [xingfudeshi](https://github.com/xingfudeshi)
- [hadoop835](https://github.com/hadoop835)
- [a364176773](https://github.com/a364176773)
- [DroidEye2ONGU](https://github.com/DroidEye2ONGU)


Also, we receive many valuable issues, questions and advices from our community. Thanks for you all.
