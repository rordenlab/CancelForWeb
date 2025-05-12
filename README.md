# CancelForWeb

Spatial neglect is a common impairment seen after right-hemisphere injury. This syndrome is often assessed with cancellation tasks, which can also guide [prognosis](https://pubmed.ncbi.nlm.nih.gov/39944743/). This web-based test provides similar functionality to the desktop [Cancel](https://github.com/neurolabusc/Cancel) application.

# Usage

 - Open the web page [https://rordenlab.github.io/CancelForWeb/](https://rordenlab.github.io/CancelForWeb/) and select the desired test (e.g. bells or letters) from the first pulldown-menu. At this stage, you can demonstrate the task, illustrating the targets. Next, choose the `Mode: test` from the pull down menu. At this stage, the task is to click on all the targets on the screen. Once all targets have been found, press the hamburger icon (`☰`) to return to the `Mode: describe`. You will be asked to save the test. Note that the status bar at the bottom will provide a few measures, including the `CoC` (Center of Cancellation).
 - The data files generated log not only which targets have been found, but also the order and timing of the search, which can provide [useful parameters for understanding neglect](https://pubmed.ncbi.nlm.nih.gov/25381020/).
 - Note that you can also use these web pages to transcribe paper-and-pencil tests, but the order and timing information will not be meaningful.
 
 # Development

It is easy to modify this web page by working with a hot-reloadable web page. Since this software uses a permissive license, you can easily fork this project and make your own variations using the free Github pages functionality.

```
git clone https://github.com/rordenlab/CancelForWeb
cd CancelForWeb
npm install
npm run dev
```

The file format used is the archaic Windows text .INI format used for legacy initialization files. If this software was created from scratch, it would have been easier to use JSON files. However, these files are compatible with the (desktop version)[https://pubmed.ncbi.nlm.nih.gov/20433859/], which does provide nice tools for creating new tests.

# Links

 - Binder et al. ([1992](https://pubmed.ncbi.nlm.nih.gov/1444886/)) described the CoC measure.
 - Rorden et al. ([2010](https://pubmed.ncbi.nlm.nih.gov/20433859/)) provide desktop tools for assessing neglect.
 - Dalmaijer et al. ([2015 ](https://pubmed.ncbi.nlm.nih.gov/25381020/)) provide Python tools for cancellation measures.
 - Röhrig et al. ([2025](https://pubmed.ncbi.nlm.nih.gov/39944743/)) describe how the center of cancellation can be used to predict outcome, aided by a [web page](https://niivue.github.io/niivue-neglect/).
 - Rosenzopf et al. [2022](https://pubmed.ncbi.nlm.nih.gov/36303420/) note that CoC is relatively robust for format and size, which is useful for a web-based test.
