---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "पैकेज आउटपुट दस्तावेज़ और उसके संसाधनों को इंस्टैंशिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.viewer.interfaces/
---

पैकेज आउटपुट दस्तावेज़ और उसके संसाधनों को इंस्टैंशिएट और रिलीज़ करने के लिए इंटरफ़ेस प्रदान करता है।


इन इंटरफ़ेसों का उपयोग आउटपुट फ़ाइल, पृष्ठों और HTML संसाधनों से जुड़े स्ट्रीम और URL के निर्माण और रिलीज़ को प्रबंधित करने के लिए किया जाता है।

इस पैकेज में मुख्य इंटरफ़ेस हैं:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


इन इंटरफ़ेसों के साथ काम करने और GroupDocs.Viewer में आउटपुट दस्तावेज़ तथा संसाधन हैंडलिंग को कस्टमाइज़ करने के बारे में अधिक विवरण के लिए,
कृपया देखें [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | एक इंटरफ़ेस का प्रतिनिधित्व करता है जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | एक इंटरफ़ेस का प्रतिनिधित्व करता है जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | एक इंटरफ़ेस का प्रतिनिधित्व करता है जो आउटपुट HTML संसाधन डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है। |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | एक इंटरफ़ेस का प्रतिनिधित्व करता है जो HTML संसाधन के लिए URL बनाता है। |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है। |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | आउटपुट फ़ाइल स्ट्रीम को इंस्टैंशिएट और रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | आउटपुट पृष्ठ स्ट्रीम को इंस्टैंशिएट और रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | CreateFileStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंशिएट किए गए इंटरफ़ेस को रिलीज़ करता है। |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | CreatePageStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंशिएट किए गए स्ट्रीम को रिलीज़ करता है। |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | CreateResourceStream इंटरफ़ेस से जुड़े मेथड द्वारा इंस्टैंशिएट किए गए स्ट्रीम को रिलीज़ करता है। |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | एक संसाधन URL बनाने, इंस्टैंशिएट करने और आउटपुट HTML संसाधन स्ट्रीम को रिलीज़ करने के लिए आवश्यक मेथड्स को परिभाषित करता है। |
