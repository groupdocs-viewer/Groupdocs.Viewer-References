---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "पैकेज आउटपुट दस्तावेज़ और उसकी संसाधनों को इंस्टैंशिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.viewer.interfaces/
---

पैकेज आउटपुट दस्तावेज़ और उसकी संसाधनों को इंस्टैंशिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।

ये इंटरफ़ेस आउटपुट फ़ाइल, पेज और HTML संसाधनों से जुड़े स्ट्रीम और URL के निर्माण और रिलीज़ को प्रबंधित करने के लिए उपयोग किए जाते हैं।

इस पैकेज में मुख्य इंटरफ़ेस हैं:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

इन इंटरफ़ेस के साथ काम करने और GroupDocs.Viewer में आउटपुट दस्तावेज़ और संसाधन हैंडलिंग को अनुकूलित करने के बारे में अधिक विवरण के लिए, कृपया [GroupDocs.Viewer Documentation][] देखें।


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | एक इंटरफ़ेस को दर्शाता है जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है। |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | एक इंटरफ़ेस को दर्शाता है जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है। |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | एक इंटरफ़ेस को दर्शाता है जो आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है। |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | एक इंटरफ़ेस को दर्शाता है जो HTML संसाधन के लिए URL बनाता है। |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है। |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | आउटपुट फ़ाइल स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | आउटपुट पृष्ठ स्ट्रीम को इंस्टैंसिएट और रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | CreateFileStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंसिएट किए गए इंटरफ़ेस को रिलीज़ करता है। |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | CreatePageStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंसिएट किए गए स्ट्रीम को रिलीज़ करता है। |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | CreateResourceStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंसिएट किए गए स्ट्रीम को रिलीज़ करता है। |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | संसाधन URL बनाने, इंस्टैंसिएट करने और आउटपुट HTML संसाधन स्ट्रीम को रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
