# Podcast Languages

Podcast Language is defined in the `channel`part of an RSS as `<language>en-US</language>`, this particular definition declares **English** and **US, United States of America** variant. This is default as RSS and Podcasting in large were invented in the USA.

But Podcasting is larger that just one language and a default definition.

ISO-639 and it's sub-variants declare about 7000 spoken languages, minus the signed languages as they does make any sense in a spoken context as audio podcasts are.

These definitions has been collected and arranged to enable language tagging in a podcasting context to allow for a much more fine-grained mapping of languages, most podcasting hosting companies are running an outdated and sometimes flat out wrong list of defined languages.



## Resources

My intentions are to give podcast hosting companies/actors a way of easily find information, even pre-built definitions to either use directly or to derive from, but essentially give them a way of adding over 7000 spoken languages, for their users to choose from. By letting podcasters/producers choose from a larger set of possible languages, most of them would choose the actual spoken language of their podcast, not defaulting to `en-us`or `en .. or worse, an ***EMPTY*** language declaration. 





### Sources

To be able to build this, a number of sources of information was used;

ISO, [International Organization for Standardization](https://www.iso.org/) 

The ISO-639 https://en.wikipedia.org/wiki/ISO_639

ISO-639-1: https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes

ISO-639-2: https://en.wikipedia.org/wiki/List_of_ISO_639-2_codes

ISO-639-3: https://en.wikipedia.org/wiki/List_of_ISO_639-3_codes

Coordinated and other information: https://glottolog.org/glottolog/language





### Pre-built

For ease of use, the following resources are pre-built for easy implementation, both for developers of podcast hosting platforms and podcast catcher mobile applications, where language-tagging of podcasts makes sense.

| Format                                       | Inteded use                                                  |
| -------------------------------------------- | ------------------------------------------------------------ |
| [YAML Source](./yaml/podcast-languages.yaml) | This is the information ORIGIN, this is what everything is built from. |
| JSON                                         | JSON with all definitions, quite large but should provide coverage of all defefined languages. (Not implemented yet) |
| XML                                          | XML with all definitions, quite large but should provide coverage of all defined languages. (Not Implemented yet) |
| HTML5 Select Element                         | HTML5 Select element with option elements. (Not implemented yet) |

 

## Participate, help out, correct

This project is currently run by a single individual, doing corrections, additions on spare time. You are welcome to send PR to help out.





This is a part of the [PodcastIndex.org](https://podcastindex.org/) initiative and an effort to bring podcasting forward.

I am [Christopher](https://christopherisene.se/), "The Swedish Trickler"



 

