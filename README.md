# OpenSpeaks Before AI*
_A set of frameworks for creating the AI/ML building blocks for low-resource languages_.

[![DOI](https://zenodo.org/badge/419524229.svg)](https://zenodo.org/badge/latestdoi/419524229) <br/>
[![ISBN](https://user-images.githubusercontent.com/1258090/188664488-a3e5a3e4-d186-4ea8-89fd-578522ad0bd9.svg)](https://theofdn.org/activities/before/)

This experimental initiative by [O Foundation](https://theofdn.org) aims to understand and document the challenges many low-resourced language speakers face. We implemented the initiative in August-September 2021 as a part of the [MozFest Trustworthy AI Working Groups program](https://web.archive.org/web/20210304203547/https://www.mozillafestival.org/en/get-involved/building-trustworthy-ai-working-group/), a cohort by the Mozilla Foundation around building trustworthy AI.

AI and ML affect everybody, whether or not they get to participate in building the massive datasets that drive AI/ML research and development. However, historically-oppressed communities, including but not limited to Black, ethnolinguistic minority communities, and poor-income communities all around the world, Dalit-Bahujan-Adivasi communities in South Asia, often have very little say about the data that is collected to build AI/ML models. Those in the research/solution-building side of the equation do not often have interest, know-how, or resource.

Our initial goal during the Working Group program was to study a few existing platforms by open-auditing. By looking at our findings from the audits, we planned to create a set of frameworks so others can identify the sociolinguistic and other anthropological gaps critical to people and data. Our understanding of digital biases is influenced by a wide range of feminist literature, particularly that of collectives such as WhoseKnowledge? and Equality Labs. Two studies inspired our approach: a seminal paper titled "Datasheets for datasets" ([Gebru et al. 2021](#references)), focusing on identifying gaps and biases in datasets, and our research on the monetization of web content in two Adivasi languages of India (Ho and Santali). During this process, we asked ourselves, "how could speakers of low-resource languages audit a platform based on their socioeconomic context?".

## Context on colonial and post-colonial caste oppression

The caste system in South Asia prevalent in the Hindu-majority societies before the European colonization got only aggravated during the colonization as the British settlers used caste discrimination to divide and rule. Today, almost all Dalit-Bahujan-Adivasi (an umbrella term often used to denote the most marginalized communities in the region) peoples, the majority of India, are oppressed socioeconomically by the minority privileged, known as the "upper castes" ([Bijoy 2003](#references)). As a result of such historical oppression, languages and dialects spoken by the oppressed communities are poorly represented on the internet, and such communities have significantly lower participation online ([Acey et al. 2021](#references)). Quite naturally, their poor affordability and access also result in flawed, biased, and uninformed training data collection with the moral rights owners of this data with little agency. We recognize systemic oppression as a fundamental problem behind the growth of most languages in digital spaces, including the internet. This impact is also evident today from the stark contrast between the steep increase in the use of dominant languages, and the poor technical support available to many low-resource languages and the low representation of Dali-Bahujan-Adivasi communities in the Indian media ([Nagarajan 2015](#references)).

## Digital context
Unlike speakers of the dominant languages, native speakers of many indigenous, endangered, and low-resource languages experience a range of critical issues while using their languages digitally. Such problems are hardly documented or considered, while AI-based solutions are professed. Most things on the internet are structured keeping in mind the needs of the well-established and dominant languages. In reality, people use (or want to use) languages that are not written using the usual suspects' writing systems: Latin, Cyrillic, right-to-left scripts, or the Chinese-Japanese-Korean scripts. A significant number of speakers speak languages that are not written but are only spoken in different settings.

## Updates
* 2022-03-09: Mozilla Festival 2022 presentation titled "[Low-resource languages, and their open source AI/ML solutions through a radical empathy lens](https://pretalx.com/mozfest-2022/talk/review/EZY97GMNEH9Y3SLWEYV8GAZ37XK98G3M)" based on open-auditing of Mozilla Common Voice for Santali language.
* 2021-11-30: A Python-based script, [originally written](https://github.com/tshrinivasan/tamil-wikipedia-word-list) by Tamil-language Wikipedia editor T. Shrinivasan, [customized](https://github.com/ofdn/odia-wordlist-from-wikimedia-dump) for extracting a wordlist from any messy text in Odia (_can be tweaked to work for other writing systems_).
* 2021-11-30: Sample [Linguistic Data](https://github.com/ofdn/OpenSpeaks-Before-AI/tree/main/data) folder with wordlists starting in three languages -- Ho (indigenous language from India; 1.4 million native speakers; 5,127 words in wordlist when reported), Odia (dominant language from India, ~40 million native speakers; 514,868 words in wordlist) and Santali (indigenous language from India; ~8 million native speakers; 127,359 words in wordlist)
* 2021-12-01: [Workshop On Media Creation In The Ho Language](https://en.iyil2019.org/events/workshop-on-media-creation-in-the-ho-language/) planned and announced to be held on December in collaboration with Birbasa (Veer Birsa Munda Ho Students Union, Odisha). The goal of this workshop is to learn about the audiovisual media content landscape in the Ho language, led equipment and provide a capacity-building training for creating audio recording of pronunciations of words, and work together for UNESCO's International Decade of Indigenous Languages campaign.

## Acknowledgment
We acknowledge that our ability and affordability are a direct impact of our own historical privileges through caste and gender. We continue to unlearn and learn from many Dalit-Adivasi-Bahujan and other systemically-oppressed scholars. However, learning is gradual, and we are prone to mistakes, whatever the intentions.

# References
Gebru, Timnit, et al. “Datasheets for Datasets.” Communications of the ACM, vol. 64, no. 12, Nov. 2021, pp. 86–92. December 2021, https://doi.org/10.1145/3458723.

Acey, Camille E., et al. “Decolonizing the Internet by Decolonizing Ourselves: Challenging Epistemic Injustice through Feminist Practice.” Global Perspectives, vol. 2, no. 1, Feb. 2021. online.ucpress.edu, https://doi.org/10.1525/gp.2021.21268.

Bijoy, C. R. "The Adivasis of India-A History of Discrimination, Conflict, and Resistance." PUCL Bulletin (2003).

Nagarajan, Kedar. 2015. “‘A Largely Upper-Caste Media Is Not Good for India’s Democracy.’” The Wire. September 9, 2015. https://thewire.in/media/a-largely-upper-caste-media-is-not-good-for-indias-democracy.

Panigrahi, Subhashish, Prasanta Hembram, and Ganesh Birua. 2021. “Research: Understanding Web Content Monetization in the Ho and Santali Languages.” Bhubaneswar: O Foundation. https://meta.wikimedia.org/wiki/Research:Understanding_Web_Content_Monetization_in_the_Ho_and_Santali_Languages.

# Join
If you are speaker of an indigenous or a low-resource language, please [join us](https://github.com/ofdn/Lang-Lintel/discussions) to share your learning and collaborate in building a more diverse, equitable, and community-run strategy for imagining AI/ML to benefit low-resource languages.

## Project team
* Prasanta Hembram (Santali-language lead starting August 2022)
* Subhashish Panigrahi (project lead)
* Sailesh Patnaik (during MozFest 2022)

## License
This project uses a three-license structure: all documentations are in a Creative Commons Share-Alike License called [CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/), all databases are under a [CC0 1.0](https://creativecommons.org/share-your-work/public-domain/cc0/) License (see [here](https://github.com/ofdn/Foundational-Language-Tech/blob/main/LICENSE) and all software are under a [MPL 2.0 License](https://www.mozilla.org/media/MPL/2.0/index.48a3fe23ed13.txt).

## Cite
If you use the framework or any part of this research, please copy the appropriate format from below. The individual datasets have a list of contributors and we encourage you to attribute them albeit the data being released under a CC0 1.0 release.

* bibTEX
```
@misc{openspeaks_2021,
	title = {OpenSpeaks {Before AI}},
	copyright = {CC0-1.0},
	url = {https://github.com/ofdn/OpenSpeaks-Before-AI},
	abstract = {A set of frameworks for creating the building blocks for low-resource languages.},
	urldate = {2022-10-05},
	publisher = {O Foundation},
	author = {Panigrahi, Subhashish},
	month = dec,
	year = {2022},
	doi = {10.5281/zenodo.7086414},
	isbn = {978-81-958409-2-2},
	note = {original-date: 2021-10-20T23:57:09Z},
	keywords = {ai, languages, low-resource-languages, ml},
}
```
* Chicago

```
Panigrahi, Subhashish. (2021) 2021. OpenSpeaks Before AI: A Set Of Frameworks For Creating The AI/ML Building Blocks For Low-Resource Languages	. O Foundation. https://github.com/ofdn/OpenSpeaks-Before-AI/.
```
