29 June 2007                   GNU LESSER GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. [http://fsf.org/]
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.


  This version of the GNU Lesser General Public License incorporates
the terms and conditions of version 3 of the GNU General Public
License, supplemented by the additional permissions listed below.

  0. Additional Definitions.

  As used herein, "this License" refers to version 3 of the GNU Lesser
General Public License, and the "GNU GPL" refers to version 3 of the GNU
General Public License.

  "The Library" refers to a covered work governed by this License,
other than an Application or a Combined Work as defined below.

  An "Application" is any work that makes use of an interface provided
by the Library, but which is not otherwise based on the Library.
Defining a subclass of a class defined by the Library is deemed a mode
of using an interface provided by the Library.

  A "Combined Work" is a work produced by combining or linking an
Application with the Library.  The particular version of the Library
with which the Combined Work was made is also called the "Linked
Version".

  The "Minimal Corresponding Source" for a Combined Work means the
Corresponding Source for the Combined Work, excluding any source code
for portions of the Combined Work that, considered in isolation, are
based on the Application, and not on the Linked Version.

  The "Corresponding Application Code" for a Combined Work means the
object code and/or source code for the Application, including any data
and utility programs needed for reproducing the Combined Work from the
Application, but excluding the System Libraries of the Combined Work.

  1. Exception to Section 3 of the GNU GPL.

  You may convey a covered work under sections 3 and 4 of this License
without being bound by section 3 of the GNU GPL.

  2. Conveying Modified Versions.

  If you modify a copy of the Library, and, in your modifications, a
facility refers to a function or data to be supplied by an Application
that uses the facility (other than as an argument passed when the
facility is invoked), then you may convey a copy of the modified
version:

   a) under this License, provided that you make a good faith effort to
   ensure that, in the event an Application does not supply the
   function or data, the facility still operates, and performs
   whatever part of its purpose remains meaningful, or

   b) under the GNU GPL, with none of the additional permissions of
   this License applicable to that copy.

  3. Object Code Incorporating Material from Library Header Files.

  The object code form of an Application may incorporate material from
a header file that is part of the Library.  You may convey such object
code under terms of your choice, provided that, if the incorporated
material is not limited to numerical parameters, data structure
layouts and accessors, or small macros, inline functions and templates
(ten or fewer lines in length), you do both of the following:

   a) Give prominent notice with each copy of the object code that the
   Library is used in it and that the Library and its use are
   covered by this License.

   b) Accompany the object code with a copy of the GNU GPL and this license
   document.

  4. Combined Works.

  You may convey a Combined Work under terms of your choice that,
taken together, effectively do not restrict modification of the
portions of the Library contained in the Combined Work and reverse
engineering for debugging such modifications, if you also do each of
the following:

   a) Give prominent notice with each copy of the Combined Work that
   the Library is used in it and that the Library and its use are
   covered by this License.

   b) Accompany the Combined Work with a copy of the GNU GPL and this license
   document.

   c) For a Combined Work that displays copyright notices during
   execution, include the copyright notice for the Library among
   these notices, as well as a reference directing the user to the
   copies of the GNU GPL and this license document.

   d) Do one of the following:

       0) Convey the Minimal Corresponding Source under the terms of this
       License, and the Corresponding Application Code in a form
       suitable for, and under terms that permit, the user to
       recombine or relink the Application with a modified version of
       the Linked Version to produce a modified Combined Work, in the
       manner specified by section 6 of the GNU GPL for conveying
       Corresponding Source.

       1) Use a suitable shared library mechanism for linking with the
       Library.  A suitable mechanism is one that (a) uses at run time
       a copy of the Library already present on the user's computer
       system, and (b) will operate properly with a modified version
       of the Library that is interface-compatible with the Linked
       Version.

   e) Provide Installation Information, but only if you would otherwise
   be required to provide such information under section 6 of the
   GNU GPL, and only to the extent that such information is
   necessary to install and execute a modified version of the
   Combined Work produced by recombining or relinking the
   Application with a modified version of the Linked Version. (If
   you use option 4d0, the Installation Information must accompany
   the Minimal Corresponding Source and Corresponding Application
   Code. If you use option 4d1, you must provide the Installation
   Information in the manner specified by section 6 of the GNU GPL
   for conveying Corresponding Source.)

  5. Combined Libraries.

  You may place library facilities that are a work based on the
Library side by side in a single library together with other library
facilities that are not Applications and are not covered by this
License, and convey such a combined library under terms of your
choice, if you do both of the following:

   a) Accompany the combined library with a copy of the same work based
   on the Library, uncombined with any other library facilities,
   conveyed under the terms of this License.

   b) Give prominent notice with the combined library that part of it
   is a work based on the Library, and explaining where to find the
   accompanying uncombined form of the same work.

  6. Revised Versions of the GNU Lesser General Public License.

  The Free Software Foundation may publish revised and/or new versions
of the GNU Lesser General Public License from time to time. Such new
versions will be similar in spirit to the present version, but may
differ in detail to address new problems or concerns.

  Each version is given a distinguishing version number. If the
Library as you received it specifies that a certain numbered version
of the GNU Lesser General Public License "or any later version"
applies to it, you have the option of following the terms and
conditions either of that published version or of any later version
published by the Free Software Foundation. If the Library as you
received it does not specify a version number of the GNU Lesser
General Public License, you may choose any version of the GNU Lesser
General Public License ever published by the Free Software Foundation.

  If the Library as you received it specifies that a proxy can decide
whether future versions of the GNU Lesser General Public License shall
apply, that proxy's public statement of acceptance of any version is
permanent authorization for you to choose that version for the
Library.# @puppeteer/replay

<!-- [START badges] -->

[![Build status](https://github.com/puppeteer/replay/workflows/run-checks/badge.svg)](https://github.com/puppeteer/replay/actions?query=workflow%3Arun-checks) [![npm puppeteer package](https://img.shields.io/npm/v/@puppeteer/replay.svg)](https://npmjs.org/package/@puppeteer/replay)

<!-- [END badges] -->

###### [API](https://github.com/puppeteer/replay/blob/main/docs/api) | [Contributing](https://github.com/puppeteer/replay/blob/main/docs/contributing.md)

> Puppeteer Replay is a library that provides an API to replay and stringify recordings created using [Chrome DevTools Recorder](https://developer.chrome.com/docs/devtools/recorder/)

## Installation

```
npm install @puppeteer/replay --save
```

If you want to replay recordings using Puppeteer, install Puppeteer as well:

```
npm install puppeteer --save
```

## Getting started with Puppeteer Replay

You can use Puppeteer Replay to:

1. **Replay recording**. Replay recording with CLI or using [the replay lib API](/examples/replay-from-file-using-puppeteer/main.js).
2. **Customize replay**. Customize how a recording is run. For example, capture screenshots after each step or integrate with 3rd party libraries.
3. **Transform recording**. Customize how a recording is stringified. For example, transform the recording into another format.

Also, you can use third-party integrations that build on top of `@puppeteer/replay`, which includes:

Transform JSON user flows to custom scripts:

- [Cypress Chrome Recorder](https://github.com/cypress-io/cypress-chrome-recorder). You can use it to convert user flow JSON files to Cypress test scripts. Watch this [demo](https://youtu.be/4qYs2bMz4GI) to see it in action.
- [Nightwatch Chrome Recorder](https://github.com/nightwatchjs/nightwatch-chrome-recorder). You can use it to convert user flow JSON files to Nightwatch test scripts.
- [WebdriverIO Chrome Recorder](https://github.com/webdriverio/chrome-recorder). You can use it to convert user flow JSON files to WebdriverIO test scripts.

Replay JSON user flows:

- [Replay with TestCafe](https://testcafe.io/documentation/403998/guides/experimental-capabilities/chrome-replay-support). You can use TestCafe to replay user flow JSON files and generate test reports for these recordings.
- [Replay with Sauce Labs](https://saucelabs.com/blog/how-to-create-test-scripts-using-chrome-devtools). You can replay the JSON files on [Sauce Labs](https://saucelabs.com/) using [saucectl](https://github.com/saucelabs/saucectl-replay-example).

## 1. Replay recording

Download this [example recording](https://storage.googleapis.com/web-dev-uploads/file/dPDCek3EhZgLQPGtEG3y0fTn4v82/vzQbv2rUfTz2DEmx06Gv.json) and save it as `recording.json`.

Using CLI + npx:

```
npx @puppeteer/replay recording.json
```

Using CLI + package.json:

In your `package.json` add a new script to invoke the `replay` command:

```json
{
  "scripts": {
    "replay": "replay recording.json"
  }
}
```

You can also give folder name as a parameter to run all the files in a folder.

Using CLI + npx:

```bash
npx @puppeteer/replay all-recordings # runs all recordings in the "all-recordings" folder.
```

Using CLI + package.json:

```json
{
  "scripts": {
    "replay": "replay all-recordings"
  }
}
```

Set the `PUPPETEER_HEADLESS` environment variable or `--headless` CLI flag to control whether the browser is started in a headful or headless mode. For example,

```
PUPPETEER_HEADLESS=true npx @puppeteer/replay recording.json # runs in headless mode, the default mode.
PUPPETEER_HEADLESS=false npx @puppeteer/replay recording.json # runs in headful mode.
PUPPETEER_HEADLESS=chrome npx @puppeteer/replay recording.json # runs in the new experimental headless mode.
```

Use the `--extension` CLI flag to provide a [custom replay extension](https://github.com/puppeteer/replay#2-customize-replay) for running the recording. For [example](https://github.com/puppeteer/replay/blob/main/examples/cli-extension/extension.js),

```sh
npx @puppeteer/replay --extension examples/cli-extension/extension.js recording.json
```

Run `npx @puppeteer/replay --help` to see all CLI options.

Using [the replay lib API](/examples/replay-from-file-using-puppeteer/main.js):

```js
import { createRunner, parse } from '@puppeteer/replay';
import fs from 'fs';

// Read recording for a file.
const recordingText = fs.readFileSync('./recording.json', 'utf8');
// Validate & parse the file.
const recording = parse(JSON.parse(recordingText));
// Create a runner and execute the script.
const runner = await createRunner(recording);
await runner.run();
```

## 2. Customize replay

The library offers a way to customize how a recording is run. You can extend
the `PuppeteerRunnerExtension` class as shown in the example below.

Full example of the `PuppeteerRunnerExtension`: [link](/examples/extend-runner/main.js)

```js
import { createRunner, PuppeteerRunnerExtension } from '@puppeteer/replay';
import puppeteer from 'puppeteer';

const browser = await puppeteer.launch({
  headless: true,
});

const page = await browser.newPage();

class Extension extends PuppeteerRunnerExtension {
  async beforeAllSteps(flow) {
    await super.beforeAllSteps(flow);
    console.log('starting');
  }

  async beforeEachStep(step, flow) {
    await super.beforeEachStep(step, flow);
    console.log('before', step);
  }

  async afterEachStep(step, flow) {
    await super.afterEachStep(step, flow);
    console.log('after', step);
  }

  async afterAllSteps(flow) {
    await super.afterAllSteps(flow);
    console.log('done');
  }
}

const runner = await createRunner(
  {
    title: 'Test recording',
    steps: [
      {
        type: 'navigate',
        url: 'https://wikipedia.org',
      },
    ],
  },
  new Extension(browser, page, 7000)
);

await runner.run();

await browser.close();
```

## 3. Transform recording

You can customize how a recording is stringified and use it to transform the recording format.

### Stringify a recording as a Puppeteer script

```js
import { stringify } from '@puppeteer/replay';

console.log(
  await stringify({
    title: 'Test recording',
    steps: [],
  })
);
```

### Customize how a recording is stringified

You can customize how a recording is stringified by extending the `PuppeteerStringifyExtension` class as shown in the example below.

Full example of `PuppeteerStringifyExtension` : [link](/examples/extend-stringify/main.js)

```js
import { stringify, PuppeteerStringifyExtension } from '@puppeteer/replay';

class Extension extends PuppeteerStringifyExtension {
  // beforeAllSteps?(out: LineWriter, flow: UserFlow): Promise<void>;
  async beforeAllSteps(...args) {
    await super.beforeAllSteps(...args);
    args[0].appendLine('console.log("starting");');
  }

  // beforeEachStep?(out: LineWriter, step: Step, flow: UserFlow): Promise<void>;
  async beforeEachStep(...args) {
    await super.beforeEachStep(...args);
    const [out, step] = args;
    out.appendLine(`console.log("about to execute step ${step.type}")`);
  }

  // afterEachStep?(out: LineWriter, step: Step, flow: UserFlow): Promise<void>;
  async afterEachStep(...args) {
    const [out, step] = args;
    out.appendLine(`console.log("finished step ${step.type}")`);
    await super.afterEachStep(...args);
  }

  // afterAllSteps?(out: LineWriter, flow: UserFlow): Promise<void>;
  async afterAllSteps(...args) {
    args[0].appendLine('console.log("finished");');
    await super.afterAllSteps(...args);
  }
}

console.log(
  await stringify(
    {
      title: 'Test recording',
      steps: [
        {
          type: 'navigate',
          url: 'https://wikipedia.org',
        },
      ],
    },
    {
      extension: new Extension(),
      indentation: '	', // use tab to indent lines
    }
  )
);
```

## Others

### Test your extensions using the replay lib

The replay lib offers a canonical recording and a test page that allows to
verify that your extension produces all expected side effects on a page.

The test command supports both stringify and runner extensions. The stringify
extension will be tested by running the stringified script using node. Run the
test using the following command.

```
npx -p @puppeteer/replay replay-extension-test --ext path-to-your-extension-js
```

### Create a Chrome extension for Recorder (Available from Chrome 104 onwards)

You can create a Chrome extension for [Recorder](https://goo.gle/devtools-recorder). Refer to the [Chrome Extensions documentation](https://developer.chrome.com/docs/extensions/mv3/devtools/) for more details on how to extend DevTools.

For example, here are some of the third party extensions:

- [Cypress extension](https://chrome.google.com/webstore/detail/cypress-chrome-recorder/fellcphjglholofndfmmjmheedhomgin) lets you export JSON user flows as [Cypress test script](https://github.com/cypress-io/cypress-recorder-extension). [Cypress](https://cypress.io) is a front end testing tool built for the modern web.
- [WebPageTest extension](https://chrome.google.com/webstore/detail/webpagetest-recorder-exte/eklpnjohdjknellndlnepihjnhpaimok) lets you export user flows from the Recorder directly as [WebPageTest Custom scripts](https://docs.webpagetest.org/scripting/) to measure site's performance. See [Converting user flows to WebPageTest custom scripts](https://blog.webpagetest.org/posts/introducing-the-new-webpagetest-recorder-chrome-extension/) to learn more.
- [Nightwatch extension](https://chrome.google.com/webstore/detail/nightwatch-chrome-recorde/nhbccjfogdgkahamfohokdhcnemjafjk/) lets you export JSON user flows as [Nightwatch test script](https://github.com/nightwatchjs/nightwatch-recorder-extension). [Nightwatch](https://nightwatchjs.org/) is an end-to-end testing solution for web applications and websites.
- [Testing Library extension](https://chrome.google.com/webstore/detail/testing-library-recorder/pnobfbfcnoeealajjgnpeodbkkhgiici) lets you export JSON user flows as [Testing Library script](https://github.com/nickmccurdy/testing-library-recorder-extension). [Testing Library](https://testing-library.com/) has simple and complete testing utilities that encourage good testing practices.
- [WebdriverIO extension](https://chrome.google.com/webstore/detail/webdriverio-chrome-record/pllimkccefnbmghgcikpjkmmcadeddfn?hl=en&authuser=1) lets you export JSON user flows as [WebdriverIO test script](https://github.com/webdriverio/recorder-extension). [WebdriverIO](https://webdriver.io/) is an end-to-end testing solution for web, mobile and IoT applications and websites.

This feature only available from Chrome 104 onwards. Check your current Chrome version with `chrome://version`. Consider installing [Chrome Canary](https://www.google.com/chrome/canary/) to try out cutting-edge features in Chrome.

This repository contains an [example extension](https://github.com/puppeteer/replay/tree/main/examples/chrome-extension). Once installed, the Recorder will have a new export option **Export as a Custom JSON script** in the [export dropdown](https://developer.chrome.com/docs/devtools/recorder/#export-flows).

To load the example into Chrome DevTools. Follow these steps:

1. Download the [chrome-extension](https://github.com/puppeteer/replay/tree/main/examples/chrome-extension) folder.
2. [Load the folder as unpacked extension](https://developer.chrome.com/docs/extensions/mv3/getstarted/#unpacked) in Chrome.
3. [Open a recording](https://developer.chrome.com/docs/devtools/recorder/#record) in the Recorder.
4. Click on [export](https://developer.chrome.com/docs/devtools/recorder/#export-flows). Now you can see a new **Export as a Custom JSON script** option in the export menu.

Click and watch the video demo below:

[![Demo video that shows how to extend export options in Recorder panel by adding a Chrome extension](https://user-images.githubusercontent.com/5917927/172872574-15ad8bea-142a-4972-bf1d-bf1379a955ba.png)](https://youtu.be/TCxIfbxgypQ)
