siddhi-map-binary
======================================

The **siddhi-map-binary extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi
</a> that  can be used to convert binary events to/from Siddhi events.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary/issues">Issue tracker</a>

## Latest API Docs 

Latest API Docs is <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-binary/api/1.0.7">1.0.7</a>.

## How to use 

**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support. 

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.map.binary</groupId>
        <artifactId>siddhi-map-binary</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/job/siddhi/job/siddhi-map-binary/badge/icon)](https://wso2.org/jenkins/job/siddhi/job/siddhi-map-binary/) |

---

## Features

* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-binary/api/1.0.7/#binary-sink-mapper">binary</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#sink-mapper">(Sink Mapper)</a>)*<br><div style="padding-left: 1em;"><p>This section explains how to map events processed via Siddhi in order to publish them in the <code>binary</code> format.</p></div>
* <a target="_blank" href="https://wso2-extensions.github.io/siddhi-map-binary/api/1.0.7/#binary-source-mapper">binary</a> *(<a target="_blank" href="https://wso2.github.io/siddhi/documentation/siddhi-4.0/#source-mapper">(Source Mapper)</a>)*<br><div style="padding-left: 1em;"><p>This extension is a binary input mapper that converts events received in <code>binary</code> format to Siddhi events before they are processed.</p></div>

## How to Contribute
 
  * Please report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to <a target="_blank" href="https://github.com/wso2-extensions/siddhi-map-binary/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to ensuring support for this extension in production. Our unique approach ensures that all support leverages our open development methodology and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 
