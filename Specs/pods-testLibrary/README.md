This is a test library specfile
--
After a new version of the lib is pushed to its own repo and tagged, developer should run
pod repo push [repo] NAME.podspec
to push the library's version specific Specfile into the Spec repo (so that it can be referenced by other podfiles, for instance, the App ones)
