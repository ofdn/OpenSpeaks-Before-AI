# Before AI*
_A set of frameworks for creating the AI/ML building blocks for low-resource languages_. 

This is an experimental initiative by [O Foundation](https://theofdn.org) is aimed at understanding the challenges faced by many low-resourced language speakers, and creating a set of frameworks to help create the building blocks required to build the artificial intelligence/machine learning infrastructure for such languages. The initial focus of this project is on a few South Asian languages.

The project was initiated by the O Foundation around August-September 2021 as a part of the [MozFest Trustworthy AI Working Groups program](https://web.archive.org/web/20210304203547/https://www.mozillafestival.org/en/get-involved/building-trustworthy-ai-working-group/), a cohort by the Mozilla Foundation around building trustworthy AI and making the same a reality through a collaborative practice.

## Problem
The (computational) linguistic issues with most under-resourced, especially the indigenous languages from South Asian, are complex and multi-layered. While lack of technical infrastructure and technical knowhow among the native speakers are often referred to as the key issues, these issues are often a result of the historical oppression of indigenous communities by dominant communities.

### Colonial and post-colonial caste/other ethnic dominance
The caste system in the South Asian, prevalent in the Hindu-majority societies, that was existing prior to the European colonizations has continued to contribute to the post-colonial exploitation of a wide number of Dalit-Bahujan-Adivasi (_an umbrella term often used to denote the most marginalized communities in the region_) groups. ([Bijoy 2003](#references)) Almost all Adivasi languages are have access to no or very little resources that are required for promoting their own languages. We recognize the systemic oppression as a key problem behind the growth of most languages on the digital spaces including the internet. It is evident today from the stark contrast between the the steep growth in the use of dominant languages, the poor technical support available to many low-resource languages and the low representation of Dali-Bahujan-Adivasi communities in the Indian media. ([Nagarajan 2015](#references)) From a global perspective, UNESCO estimates that half of the 6,500 languages spoken around the world are in grave danger and might get extinct in a century's time. ([Moseley 2010](#references)) The unique strategies and methodologies by such language communities are poorly documented.

## Digital context
Unlike speakers of the dominant languages, native speakers of many indigenous, endangered and low-resource languages experience a range of critical issues while trying to actively use their languages on the internet and other digital spheres. This is primarily because most things on the internet are structured keeping in mind the needs of the well established and dominant languages. In reality, languages are much beyond just Latin-based, right-to-left (e.g. Arabic, Hebrew) or the Chinese-Japanese-Korean script-based language groups. The speakers of most low-resource languages are marginalized from a financial, technical knowhow and institutional support standpoint. A majority of the world languages are oral with no standard writing system. Our initial question is "how does the internet look like for many such low-resource languages?". We are trying to unlearn our own language biases, and study the challenges of many smaller community-building exercises for future AI/ML projects. There are communities that are trying to have a Unicode encoding standard for their script, some are building a typeface to type in their native script for the first time, some are creating openly-licensed content using platforms like Wikipedia, some are donating audio pronunciations of words/sentences using projects like Lingua Libre an Common Voice, and some are building online dictionaries for the first time in their own language.

## Approach
Growing our own understanding of the systemic issues including oppression of communities as a whole and particularly, women, low-income individuals/families, people with disabilities and other subgroups with less privileges, is the first step in our work. To further this, we started studying two indigenous languages from India -- Ho and Santali -- looking closely the community-led media development. ([Panigrahi et al. 2021)(#references) To learn about the significantly low growth of the building blocks for AI/ML-based tools in many low-resource languages would require taking many steps back to learn from emerging trends within different low-resource language communities. Our hope is this learning process will help us document in the form of conceptual framing of the issues and the strategies that are essential to address some of the critical issues. We are also conscious of not overburdening many communities -- who are native speakers of our focus languages -- during our interactions which can potentially contribute to the very issues that they have been forced to deal with.

## Updates
* 2021-11-30: A Python-based script, [originally written](https://github.com/tshrinivasan/tamil-wikipedia-word-list) by Tamil-language Wikipedia editor T. Shrinivasan, [customized](https://github.com/ofdn/odia-wordlist-from-wikimedia-dump) for extracting a wordlist from any messy text in Odia (_can be tweaked to work for other writing systems_).
* 2021-11-30: Sample [Linguistic Data](https://github.com/ofdn/Foundational-Language-Tech/tree/main/data) folder with wordlists starting in three languages -- Ho (indigenous language from India; 1.4 million native speakers; 5,127 words in wordlist when reported), Odia (dominant language from India, ~40 million native speakers; 514,868 words in wordlist) and Santali (indigenous language from India; ~8 million native speakers; 127,359 words in wordlist)
* 2021-12-01: [Workshop On Media Creation In The Ho Language](https://en.iyil2019.org/events/workshop-on-media-creation-in-the-ho-language/) planned and announced to be held on December in collaboration with Birbasa (Veer Birsa Munda Ho Students Union, Odisha). The goal of this workshop is to learn about the audiovisual media content landscape in the Ho language, led equipment and provide a capacity-building training for creating audio recording of pronunciations of words, and work together for UNESCO's International Decade of Indigenous Languages campaign.

# Join
If you are speaker of an indigenous or a low-resource language, please [join us](https://github.com/ofdn/Lang-Lintel/discussions) to share your learning and collaborate in building a more diverse, equitable, and community-run strategy for imagining AI/ML to benefit low-resource languages. 

## Project team
* Subhashish Panigrahi
* Sailesh Patnaik

## License
This project uses a three-license structure: all documentations are in a Creative Commons Share-Alike License called [CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/), all databases are under a [CC0 1.0](https://creativecommons.org/share-your-work/public-domain/cc0/) License (see [here](https://github.com/ofdn/Foundational-Language-Tech/blob/main/LICENSE) and all software are under a [MPL 2.0 License](https://www.mozilla.org/media/MPL/2.0/index.48a3fe23ed13.txt).

## Cite
If you use the data or any part of this research, please copy the appropriate format from below:

* bibTEX
```
@misc{panigrahi_lang_2021,
	title = {Lang {Lintel}},
	copyright = {CC0-1.0},
	url = {https://github.com/ofdn/Lang-Lintel},
	abstract = {A set of frameworks for creating the building blocks for low-resource languages.},
	urldate = {2021-12-05},
	publisher = {O Foundation},
	author = {Panigrahi, Subhashish},
	month = dec,
	year = {2021},
	note = {original-date: 2021-10-20T23:57:09Z},
	keywords = {ai, languages, low-resource-languages, ml},
}
```
* Chicago

```
Panigrahi, Subhashish. (2021) 2021. Lang Lintel. O Foundation. https://github.com/ofdn/Lang-Lintel.
```

# References
Bijoy, C. R. "The Adivasis of India-A History of Discrimination, Conflict, and Resistance." PUCL Bulletin (2003).

Nagarajan, Kedar. 2015. “‘A Largely Upper-Caste Media Is Not Good for India’s Democracy.’” The Wire. September 9, 2015. https://thewire.in/media/a-largely-upper-caste-media-is-not-good-for-indias-democracy.

Moseley, Christopher (ed.). 2010. “UNESCO Atlas of the World’s Languages in Danger.” Paris: UNESCO Publishing. http://www.unesco.org/languages-atlas/en/statistics.html.

Panigrahi, Subhashish, Prasanta Hembram, and Ganesh Birua. 2021. “Research: Understanding Web Content Monetization in the Ho and Santali Languages.” Bhubaneswar: O Foundation. https://meta.wikimedia.org/wiki/Research:Understanding_Web_Content_Monetization_in_the_Ho_and_Santali_Languages.
