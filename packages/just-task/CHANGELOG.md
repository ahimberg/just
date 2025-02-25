# Change Log - just-task

This log was last generated on Mon, 22 Jul 2019 20:51:44 GMT and should not be manually modified.

## 0.13.1
Mon, 22 Jul 2019 20:51:44 GMT

### Patches

- fail the build if it has invalid config (kchau@microsoft.com)

## 0.13.0
Thu, 11 Jul 2019 19:35:28 GMT

### Minor changes

- returns a wrapped task even when doing a task('foo', 'bar') form (kchau@microsoft.com)

## 0.12.2
Thu, 11 Jul 2019 17:08:46 GMT

### Patches

- speeding up build cache (kchau@microsoft.com)

## 0.12.1
Fri, 05 Jul 2019 16:59:55 GMT

### Patches

- Uppercase the S in TypeScript (orta.therox@gmail.com)

## 0.12.0
Thu, 04 Jul 2019 02:04:13 GMT

### Minor changes

- added a no-op detection for packages that aren't build and have no scripts (kchau@microsoft.com)

## 0.11.3
Tue, 02 Jul 2019 20:19:42 GMT

### Patches

- making build cache more accurately determine deps that aren't using just (kchau@microsoft.com)

## 0.11.2
Mon, 01 Jul 2019 20:15:20 GMT

### Patches

- introduce ESLint to sources (43081j@users.noreply.github.com)

## 0.11.1
Mon, 01 Jul 2019 18:55:04 GMT

### Patches

- fixes build cache so packages can have different path name than package name (kchau@microsoft.com)

## 0.11.0
Thu, 13 Jun 2019 21:16:34 GMT

### Minor

- adds a bit more rigor to support build deps invalidation of cache (kchau@microsoft.com)

## 0.10.0
Tue, 04 Jun 2019 15:55:03 GMT

### Minor changes

- Adds cache capability

## 0.9.9
Wed, 15 May 2019 18:44:04 GMT

### Patches

- Switch microsoft in repo URL to lowercase

## 0.9.8
Tue, 14 May 2019 17:59:20 GMT

### Patches

- Adds __dirname resolve as last resort

## 0.9.7
Fri, 10 May 2019 17:53:27 GMT

### Patches

- Adds validation of command and a friendlier error message

## 0.9.6
Fri, 03 May 2019 19:49:20 GMT

### Patches

- Show error message if it's a string

## 0.9.5
Wed, 01 May 2019 16:12:57 GMT

### Patches

- Export the chain API from the root as well

## 0.9.4
Mon, 29 Apr 2019 21:46:55 GMT

### Patches

- More explicit error logs

## 0.9.3
Thu, 25 Apr 2019 22:19:05 GMT

### Patches

- really get rid of deprecation warning

## 0.9.2
Thu, 25 Apr 2019 21:21:58 GMT

### Patches

- get rid of logs with the wrapped task

## 0.9.1
Thu, 25 Apr 2019 18:29:49 GMT

### Patches

- gets rid of dep0097 warnings when running just tasks

## 0.9.0
Wed, 17 Apr 2019 00:09:58 GMT

### Minor changes

- Adds API to allow injecting a task after task has been registered

## 0.8.1
Sun, 24 Feb 2019 04:07:27 GMT

### Patches

- Fix breaks caused by just-task resolve using the same yargs instance to check config path

## 0.8.0
Fri, 22 Feb 2019 23:37:36 GMT

### Minor changes

- Consistent interface naming

## 0.7.10
Fri, 22 Feb 2019 19:03:38 GMT

### Patches

- Update package metadata

## 0.7.9
Fri, 22 Feb 2019 16:58:03 GMT

### Patches

- Tests and docs for resolve

## 0.7.8
Thu, 21 Feb 2019 23:25:53 GMT

### Patches

- Use new logger package

## 0.7.7
Wed, 20 Feb 2019 23:17:15 GMT

### Patches

- Lock some dep versions

## 0.7.6
Tue, 22 Jan 2019 21:28:18 GMT

### Patches

- deps update

## 0.7.5
Sat, 05 Jan 2019 20:47:28 GMT

### Patches

- Fixed: make sure to display list of tasks that didn't complete

## 0.7.4
Sat, 05 Jan 2019 19:16:15 GMT

### Patches

- Fixed: set proper exit code for cases where task function exits the process before top level task is reached

## 0.7.3
Sat, 15 Dec 2018 04:42:57 GMT

### Patches

- fix bugs with config file search

## 0.7.2
Thu, 13 Dec 2018 23:56:45 GMT

### Patches

- Fixed: config file argument now works again

## 0.7.1
Thu, 13 Dec 2018 18:16:47 GMT

### Patches

- Fixed a bug with the new thunk replacement of just returning a function

## 0.7.0
Wed, 12 Dec 2018 18:57:17 GMT

### Minor changes

- Get rid of thunk API

## 0.6.1
Wed, 12 Dec 2018 03:04:50 GMT

### Patches

- Fixed resolution logic

## 0.6.0
Sun, 09 Dec 2018 23:01:57 GMT

### Minor changes

- Adds thunk and condition meta functions

## 0.5.0
Sat, 08 Dec 2018 04:58:33 GMT

### Minor changes

- streamlines API so the logger is not from the this context

## 0.4.2
Fri, 07 Dec 2018 22:20:28 GMT

### Patches

- fix: pass the right argv to the consumers

## 0.4.1
Fri, 07 Dec 2018 22:10:50 GMT

### Patches

- fix: makes conditon() work with series and parallel

## 0.4.0
Fri, 07 Dec 2018 18:17:23 GMT

### Minor changes

- Adds a 'condition' task function that can decide whether to skip task or not

## 0.3.1
Fri, 07 Dec 2018 17:16:09 GMT

### Patches

- Adds resilience to CLI script

## 0.3.0
Wed, 05 Dec 2018 22:16:09 GMT

### Minor changes

- Rename rig bin script to just

## 0.2.0
Wed, 05 Dec 2018 22:01:31 GMT

### Minor changes

- Renamed to just

## 1.2.6
Tue, 04 Dec 2018 06:13:37 GMT

### Patches

- Fixes globally installed just-task to check for local copy

## 1.2.5
Tue, 04 Dec 2018 05:15:26 GMT

### Patches

- Fixed help command to actually list commands

## 1.2.4
Mon, 03 Dec 2018 22:48:20 GMT

### Patches

- better failure logging and documentation

## 1.2.3
Mon, 03 Dec 2018 22:24:03 GMT

### Patches

- Fixed default tasks

## 1.2.2
Mon, 03 Dec 2018 22:04:01 GMT

### Patches

- Adding tests

## 1.2.1
Mon, 03 Dec 2018 18:39:51 GMT

### Patches

- Adds better failure logging messages

## 1.2.0
Mon, 03 Dec 2018 06:31:09 GMT

### Minor changes

- Adds default task support 

## 1.1.0
Mon, 03 Dec 2018 05:18:13 GMT

### Minor changes

- Added some readme and add support for yargs command module in task definition

## 1.0.1
Mon, 03 Dec 2018 00:54:11 GMT

### Patches

- adding blank line to test publish

## 1.0.0
Sun, 02 Dec 2018 03:50:30 GMT

*Initial release*

