Reference
=========

[ ](#HowTo)

How To...
---------

[ ](#UsePackages)

### Use packages

[ ](#FindAPackage)

#### Find a package

In your browser, you can search Anaconda Cloud for packages by package
name. From the top navigation bar of any page, enter the package name in
the search box. You can filter your searches to specify only conda or
PyPI packages, and you can sort results by number of favorites or number
of downloads by clicking the search results column heading.

[ ](#DownloadAndInstallAPackageFromAnacondaCloud)

#### Download and install a package from Anaconda Cloud

To install a conda package, in your terminal window run:

    conda install -c username packagename

Conda expands "username" to a URL such as
"<https://anaconda.org/username>" or
"<https://conda.anaconda.org/username>" based on the settings in the
.condarc file. Anaconda Cloud users can use the defaults, and Anaconda
Enterprise repository users can [configure the
repository](https://docs.continuum.io/anaconda-repository/configuration)
or [configure
conda](http://conda.pydata.org/docs/config.html#set-a-channel-alias-channel-alias)
to use their local installation.

[ ](#DownloadAndInstallAPypiPackageFromAnacondaCloud)

#### Download and install a PyPI package from Anaconda Cloud

To install a PyPI package, in your terminal window run:

    pip install --index-url pypi.anaconda.org/USERNAME/simple packagename

[ ](#UseTheAnacondaClientCli)

### Use the anaconda-client CLI

[ ](#InstallAnacondaClient)

#### Install anaconda-client

The anaconda-client command line interface (CLI) is available via conda
or pip. See [installation and setup
instructions](/using.html#InstallingAnacondaClientAndAnacondaBuild).

[ ](#FindMyAnacondaClientLoginCredentials)

#### Find my anaconda-client login credentials

Your credentials for anaconda-client are those you used to create an
account on Anaconda Cloud. For help, go to Anaconda.org and click
"forgot password."

[ ](#LogIntoAnacondaClient)

#### Log into anaconda-client

After you have downloaded and configured anaconda-client, open a
terminal window and run:

    anaconda login

[ ](#SeeAListOfAnacondaClientCommands)

#### See a list of anaconda-client commands

From a terminal window, run:

    anaconda --help

[ ](#FindOutMoreAboutAnAnacondaClientCommand)

#### Find out more about an anaconda-client command

From a terminal window, run:

    anaconda COMMANDNAME -h

[ ](#SeeAListOfAllAvailableAnacondaClientConfigurationFiles)

#### See a list of all available anaconda-client configuration files

From a terminal window, run:

    anaconda config --files

[ ](#SeeAListOfAllOfMyAnacondaClientConfigurationVariables)

#### See a list of all of my anaconda-client configuration variables

From a terminal window, run:

    anaconda config --show

[ ](#FindOutMoreAboutTheAnacondaClient)

#### Find out more about the anaconda-client

If you have a question that you cannot answer using the help command,
documentation or community support email group, please [contact
us](mailto:support@anaconda.org).

[ ](#BuildPackages)

### Build packages

[ ](#BuildAndUploadAPackage)

#### Build and upload a package

See the [Anaconda Cloud Build Guide](/build.html) for step-by-step
instructions. For a quick run-through, try the Quickstart [build guide
section](/quickstart.html#BuildAndUploadPackages).

[ ](#TestABuiltPackage)

#### Test a built package

Specify the '--use-local' option. For example:

    conda create --use-local -n test PACKAGENAME

[ ](#UploadAPackageToAnacondaCloud)

#### Upload a package to Anaconda Cloud

In a terminal window, run:

    anaconda upload PACKAGENAME

[ ](#FindHelpUploadingPackages)

#### Find help uploading packages

For a complete list of upload options, including specifying a package's
channel, label, availability to other users, and metadata, in a terminal
window, run:

    anaconda upload -h

[ ](#ManageMyAccount)

### Manage my account

[ ](#BuildPrivatePackagesOrGetMorePackageStorageSpace)

#### Build private packages or get more package storage space

Upgrade to a paid plan. Log into Anaconda Cloud, from the toolbar select
User Settings &gt; Billing, and click the Change Plan button.

[ ](#Faq)

FAQ
---

[ ](#GeneralQuestions)

### General Questions

[ ](#WhatIsAnacondaCloud)

#### What is Anaconda Cloud?

Anaconda Cloud (Anaconda.org) provides a package management service and
the Anaconda Build system. Anaconda Cloud package management it easy to
find, access, store and share public and private notebooks,
environments, and conda and PyPI packages, and to keep up with updates
made to the packages and environments you're using. Anaconda Build helps
you build cross-platform packages with build workers on a cloud
computing service or on your local computer.

[ ](#WhatKindOfPackagesDoesAnacondaCloudSupport)

#### What kind of packages does Anaconda Cloud support?

Anaconda Cloud supports any type of package. Today, it's primarily used
for conda and PyPI packages, as well as notebooks and environments.

[ ](#WhoCanFindAndInstallMyPackages)

#### Who can find and install my packages?

If you have a free account, all of your packages are public, so after
you upload them to Anaconda Cloud anyone can search for and download
them. If you wish to designate private packages, you can [purchase a
paid account](https://anaconda.org/about/pricing).

[ ](#WhatIsContinuumAnalytics)

#### What is Continuum Analytics?

Continuum Analytics is a software development and consulting company of
passionate open source advocates based in Austin, Texas, USA. We are
committed to the open source community. We created the Anaconda Python
distribution and contribute to many other open source-based data
analytics tools. You can find out more about us
[here](http://continuum.io/our-story).

[ ](#WhatAreAnacondaCloudSTermsOfService)

#### What are Anaconda Cloud's Terms of Service?

You can read our terms of service
[here](https://anaconda.org/about/legal/terms). For any additional
questions, please [email us](mailto:support@anaconda.org).

[ ](#AccountsAndPricing)

### Accounts and Pricing

[ ](#HowMuchDoesAnacondaCloudCost)

#### How much does Anaconda Cloud cost?

Anaconda Cloud is always free for downloading and uploading public
packages, and for academic users. If you want private packages or extra
storage space, you can upgrade to a private account. For more
information, see our [plans and
pricing](https://anaconda.org/about/pricing).

[ ](#DoYouOfferFreeAccessForAcademicUse)

#### Do you offer free access for academic use?

Yes. Our academic accounts even include free add-ons such as IOPro and
Anaconda Accelerate. You must sign up for Anaconda Cloud with an .edu
email address. Other features such as private packages and advanced
build worker options require a paid plan.

[ ](#HowDoIGetStartedWithAnacondaCloud)

#### How do I get started with Anaconda Cloud?

You can search, download and install hundreds of public packages without
even having an account. If you wish to build and upload packages, you
will need to sign up for an [Anaconda Cloud
account](https://anaconda.org/). See our [Using Anaconda Cloud
section](/using.html) for more help.

[ ](#WhatKindOfAccountDoIHave)

#### What kind of account do I have?

By default your account is a personal, free account. All packages you
upload to Anaconda Cloud will be public, and you will be the only person
with administrative access to your account.

[ ](#WhatSIncludedInTheFreeVersionOfAnacondaCloud)

#### What's included in the free version of Anaconda Cloud?

The Free plan allows you to search for, create and host public packages,
and provides up to 3 GB storage space. [Compare
plans](https://anaconda.org/about/pricing).

[ ](#WhatSIncludedInThePaidPersonalVersionOfAnacondaCloud)

#### What's included in the paid personal version of Anaconda Cloud?

With our paid personal subscription, you can create and host private
packages, and use 10 GB of storage space. [Compare
plans](https://anaconda.org/about/pricing).

[ ](#WhatSIncludedInThePaidOrganizationVersionOfAnacondaCloud)

#### What's included in the paid organization version of Anaconda Cloud?

With our paid subscriptions, you can create and host private packages,
multiple users and groups, and use 100 GB of storage space. [Compare
plans](https://anaconda.org/about/pricing).

[ ](#HowCanIUpgradeMyAccount)

#### How can I upgrade my account?

You can upgrade to a paid account
[here](https://anaconda.org/settings/billing). This will allow you to
create private packages and increase your storage limit.

[ ](#WhatIsAnOrganizationAccountAndHowIsItDifferentFromAnIndividualAccount)

#### What is an organization account, and how is it different from an individual account?

An organization account allows multiple individual users to administer
packages and have more control of package access by other users. An
individual account is for use by one person.

[ ](#Glossary)

Glossary
--------

[ ](#Anaconda)

### Anaconda

An easy-to-install, free collection of Open Source packages, including
Python and the conda package manager, with free community support. Over
150 packages are installed with Anaconda. The Anaconda repository
contains over 250 additional Open Source packages that can be installed
or updated after installing Anaconda with the
`conda install PACKAGENAME` command.

[ ](#AnacondaCloud)

### Anaconda Cloud

Anaconda Cloud hosts hundreds of useful Python packages, notebooks and
environments for a wide variety of applications. You don't need to have
an Anaconda Cloud account, or to be logged in, to search for public
packages, download and install them. Anaconda Cloud works with the
Anaconda-Build command line interface to build packages on your local
computer. Anaconda Cloud is located at anaconda.org.

[ ](#AnacondaBuildCli)

### Anaconda-Build CLI

The command line interface (CLI) to Anaconda Cloud that lets you build
cross-platform packages with build workers on a cloud computing service
or on your local computer. Contrast to conda-build which can build
packages only for your local operating system.

[ ](#AnacondaClientCli)

### Anaconda-Client CLI

The Anaconda-Client command line interface (CLI) allows you to log into
Anaconda Cloud directly from your terminal window and manage your
account. Anaconda-Client must be installed before you can build
cross-platform packages with Anaconda-Build. It is not necessary for
downloading or installing packages from Anaconda Cloud.

[ ](#Binstar)

### Binstar

Binstar was an early project name for Anaconda Cloud. You may still see
the term Binstar in certain command and directory names.

[ ](#BuildQueue)

### Build Queue

A build queue holds new package building and testing requests (also
called "build jobs" or "builds") when a user or organization requests a
build to be created. This can be done automatically with continuous
integration (CI) with sites such as Github or manually through the user
interface.

-   A user (organization or individual) submits jobs to a queue with
    the CLI.
-   A queue may have multiple workers attached to it.
-   Most queues are private. Anaconda Cloud also offers a public queue
    for building Linux-64 packages, which can be used by any Anaconda
    Cloud user.

[ ](#BuildWorker)

### Build Worker

A build worker is a machine running the Anaconda Build client, typically
an Amazon Web Services (AWS) instance.

When a build worker is first created, it must be registered with an
Anaconda Build queue in order for the queue to know about it and
delegate incoming requests of the right type to that build worker.

-   Each worker runs on only one platform, so it can only receive and
    execute build jobs that should be executed on that platform. For
    example, to build a job for Win-32 you must create a Win-32 worker.
-   More than one worker may be attached to a queue to reduce wait time
    in the queue. There may be more than one worker for one
    operating system. For example, a queue could have two Linux-32
    workers and one Win-64 worker.
-   The worker will do the actual work of building, compiling and
    testing the package and may optionally then upload the compiled
    package to Anaconda Cloud.

[ ](#Labels)

### Labels

The URLs on Anaconda Cloud where conda looks for packages. Using the
Anaconda-Client CLI, package developers can create additional labels
such as development (labels/dev) test (labels/test) or other labels
which will be searched only if the user specifies the label.

<https://anaconda.org/travis/labels/main> - the label searched by
default

<https://anaconda.org/travis> - same as default label with "main"
implicit

<https://anaconda.org/travis/labels/dev> - contains the packages in
development

<https://anaconda.org/travis/labels/test> - contains packages ready to
test

<https://anaconda.org/travis/labels/any-custom-label> - any label you
wish to use.

[ ](#Conda)

### Conda

The conda package manager and environment manager program that installs
and updates packages and their dependencies, and lets you easily switch
between environments on your local computer.

[ ](#CondaBuild)

### Conda-Build

The command line interface that lets you build packages for your local
operating system. Contrast to Anaconda Cloud that lets you build
cross-platform packages.

[ ](#CondaPackage)

### Conda package

A tarball (compressed file) containing system-level libraries, Python
modules, executable programs, or other components.

[ ](#Miniconda)

### Miniconda

A minimal installer for conda. Like Anaconda, Miniconda is a software
package that includes the conda package manager and Python and its
dependencies, but does not include any other packages. Once conda is
installed by installing either Anaconda or Miniconda, other software
packages may be installed directly from the command line with 'conda
install'. See also Anaconda and conda.

[ ](#NoarchPackage)

### Noarch package

A conda package that contains nothing specific to any system
architecture, so it may be installed on any system. When conda does a
search for packages on any system in a channel, conda always checks both
the system-specific subdirectory, for example, `linux-64` *and* the
`noarch` directory.

[ ](#Onsite)

### OnSite

Anaconda Cloud is powered by Anaconda Server by Continuum Analytics. Run
your own Anaconda server behind firewalls or in air-gapped environments.
Contact [<sales@continuum.io>](mailto:sales@continuum.io) for more
information.

[ ](#Organization)

### Organization

An organization account is a type of account on Anaconda Cloud that
allows multiple individual users to administer packages and control
package access to different user groups. It also includes a large amount
of storage space.

[ ](#Repository)

### Repository

A storage location from which software packages may be retrieved and
installed on a computer.

[ ](#SourcePackage)

### Source package

"Source" packages are source code only, not yet built for any specific
platform, and might be compatible with all, some, or only one of the
platforms.

[ ](#Token)

### Token

A token (or authentication token) is the mechanism by which anonymous
users can download private packages without using an Anaconda Cloud
account. It is an alpha-numeric code that is inserted into a URL that
allows access by anyone who has the URL. You can use anaconda-client to
generate new tokens to give other users specifically scoped access to
packages and collections.

[ ](#UserNamespace)

### User Namespace

The part of Anaconda Cloud where a user or organization may host
packages. For example, the *user namespace*
<https://anaconda.org/travis> contains packages that were uploaded and
shared by the user named Travis.
