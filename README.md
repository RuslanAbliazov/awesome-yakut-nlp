# awesome-yakut-nlp
Yakut language processing software, models and datasets.

Native name: саха тыла (Sakha tyla) / сахалыы (Saqalıı)
Other names: Yakut, Yakut-Sakha
Language family: Turkic → Siberian (Northern) Turkic languages

[~443,312 native speakers, Том 4](https://14.rosstat.gov.ru/folder/39644) in the Sakha Republic (Yakutia), Russia.

Sakha uses a Cyrillic-based alphabet with the standard Russian letters plus additional letters for native sounds (e.g., Ҕҕ, Ҥҥ, Өө, Һһ, Үү, Дь дь, Нь нь). 

The current standard alphabet was established around 1939.

Earlier versions of the writing system used Latin-based alphabets in the 1920s–1930s (including Novgorodov’s alphabet and the Yañalif system). 
inalco.fr

Today, Sakha is officially written in Cyrillic; Latin forms are of historical and academic interest.

##  1) Annotated data

1. [UniversalDependencies](https://universaldependencies.org/treebanks/sah_yktdt/index.html) -- 299 sentences, 1459 tokens and 1460 syntactic words.
2. YakuToolkit -- Yakut Treebank and Morphological Analyzer. [Link to paper](https://aclanthology.org/2022.sigul-1.24/)
3. [Turkic Interlingua Corpus](https://github.com/turkic-interlingua/til-mt) -- 9237 parallel Russian-Sakha sentences

## 2) Not annotated data

1. [Yakut National Korpus](https://sakha-corpus.ysn.ru/index.php?k=6) -- 15 million word occurrences
2. Leontiev N. The newspaper corpus of the yakut language //PROCEEDINGS OF THE INTERNATIONAL CONFERENCE" TURKIC LANGUAGES PROCESSING" TurkLang-2015. – 2015. – С. 233-235.
3. [OSCAR‑2301 (Sakha subset)](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301) -- multilingual resources and datasets for Machine Learning (ML) and Artificial Intelligence (AI) applications, 17,566 documents(4,288,051 words) for Sakha
4. [Wikipedia dump](https://huggingface.co/datasets/wikimedia/wikipedia/viewer/20231101.sah) -- 17,098 documents, ~3,057,685 tokens
5. [uonlp/CulturaX](https://huggingface.co/datasets/uonlp/CulturaX) -- training data for LLM, 22,141 documents
6. [Yakut-Russian Parallel Corpora](https://huggingface.co/datasets/averoo/sakha-russian-parallel-corpora-all) -- 13,323 pairs of Russian-Sakha sentences
7. [Yakut-Russian Translation Dataset](https://huggingface.co/datasets/lab-ii/yakut-translate-peoples)
8. [Yakut-Russian Code-Switching Corpus](https://lingconlab.ru/cs_yakut/) -- Russian-Sakha code-switching dataset, 10 texts with a total of more than 15,000 words

## 3) Dictionaries

1. Russian-Yakut and Yakut-Russian [dictionaries](https://sakhatyla.ru/) [on Github](https://github.com/ogpetrov/sakha-nlp/blob/main/data/btsja_parsed_v01.csv) [1] -- 18,262 words
2. Comprehensive Explanatory [Dictionary](https://igi.ysn.ru/btsja/index.php?lang=ru) of the Yakut Language


## 4) NLP tools

0. [Yandex Translate](https://translate.yandex.ru/?source_lang=sah&target_lang=ru)
1. [Apertium](https://github.com/apertium/apertium-sah)
2. Zou Y., Lyles N. OzQyrqBERT-The First Steps towards a Universal Turkic Language Part-of-Speech Tagger.
3. [Morphological Analyzer](https://github.com/nicolascortegoso/yakutmorph)

## 5) Websites on Yakut(Saha) language 

1. https://sakha.ysia.ru/?utm_source=ysia
2. https://sakha-sire.ru/
3. [Ruwiki](https://sah.ruwiki.ru/wiki/%D0%A1%D2%AF%D1%80%D2%AF%D0%BD_%D1%81%D0%B8%D1%80%D1%8D%D0%B9)
4. [Wikipedia](https://sah.wikipedia.org/wiki/%D0%A1%D2%AF%D1%80%D2%AF%D0%BD_%D1%81%D0%B8%D1%80%D1%8D%D0%B9)

## 6) Phonetics

1. [Phonemizer](https://github.com/ogpetrov/sakha-nlp/blob/main/code/phonetics/sakha_phonemizer.py) [1]

## 7) LLM

1. [Qwen/Qwen3-14B](https://huggingface.co/lab-ii/Aina-14B-Instruct-01-10-2025)

    [pretrain](https://huggingface.co/datasets/ailabykt/sakha-corpus-mono) -- ~232K rows

    [SFT](https://huggingface.co/datasets/lab-ii/sakha_chat_ml-sft) -- 10,350 pairs
2. [jhu-clsp/mmBERT-base](https://huggingface.co/jhu-clsp/mmBERT-base) -- Sakha mentioned on model page, 307M params
3. [bamaxi/ruBert-base-sakha](https://huggingface.co/bamaxi/ruBert-base-sakha) -- 200M params
4. [ai-forever/mGPT-1.3B-yakut](https://huggingface.co/ai-forever/mGPT-1.3B-yakut)

## 8) Semantic

1. [MTEB task dataset(classify language by text)](https://huggingface.co/datasets/mteb/CyrillicTurkicLangClassification) -- Cyrillic dataset of 8 Turkic languages spoken in Russia and former USSR

## 9) Research groups

1. SIGTURK—ACL -- An ACL Special Interest Group focusing on research in computational linguistics (NLP) for Turkic languages
2. TurkLang -- A long-running international conference series on computational and linguistic aspects of Turkic languages (text processing, corpora, MT, speech tech, etc.).
3. Turkic Languages -- biannual peer-reviewed journal
4. Northwest Linguistics Conference 

## 10) Other sources

1. [1] https://github.com/ogpetrov/sakha-nlp