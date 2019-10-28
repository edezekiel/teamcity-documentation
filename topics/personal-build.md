[//]: # (title: Personal Build)
[//]: # (auxiliary-id: Personal Build)

A _personal build_ is a build-out of the common builds sequence which typically uses the changes not yet committed into the version control. Personal builds are usually initiated from one of the [supported IDEs](supported-platforms-and-environments.md#Remote+Run+and+Pre-tested+Commit) via the [Remote Run](remote-run.md) procedure.

A personal build uses the current VCS repository sources plus the changed files identified during the remote run initiation. The results of a personal build can be seen in the "My Changes" view of the corresponding IDE plugin and on the __[Changes](viewing-your-changes.md)__ page in TeamCity. Finished personal builds are listed in the [build history](build-history.md), but only for the users who initiated them.   
Read more about running commits via Remote Run in [Pre-Tested (Delayed) Commit](pre-tested-delayed-commit.md).

By default, users only see their own personal builds in the build lists, but this can be changed via the "_Show all personal builds_" option in __My Settings & Tools | General | UI settings__ of the [user profile](managing-your-user-account.md).

You can also mark a build as _personal_ using the corresponding option of the [Run](triggering-a-custom-build.md) dialog.   
By default, only users with the Project Developer [role](role-and-permission.md) can initiate a personal build.

It is possible to [restrict running personal builds](configuring-general-settings.md#Allow+Triggering+Personal+Builds) in the __General Settings__ of a build configuration.

 __  __

__See also:__

__Concepts__: [Pre-tested Commit](pre-tested-delayed-commit.md) | [Remote Run](remote-run.md)   
__Installing Tools__: [IntelliJ Platform Plugin](intellij-platform-plugin.md) | [Eclipse Plugin](eclipse-plugin.md) | [Visual Studio Addin](visual-studio-addin.md)   
__Troubleshooting__: [Remote Run Problems](reporting-issues.md)

__ __