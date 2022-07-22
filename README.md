---
license: bigscience-bloom-rail-1.0
language:
- ak
- ar
- as
- bm
- bn
- ca
- code
- en
- es
- eu
- fon
- fr
- gu
- hi
- id
- ig
- ki
- kn
- lg
- ln
- ml
- mr
- ne
- nso
- ny
- or
- pa
- pt
- rn
- rw
- sn
- st
- sw
- ta
- te
- tn
- ts
- tum
- tw
- ur
- vi
- wo
- xh
- yo
- zh
- zu
programming_language: 
- C
- C++
- C#
- Go
- Java
- JavaScript
- Lua
- PHP
- Python
- Ruby
- Rust
- Scala
- TypeScript
pipeline_tag: text-generation
widget:
- text: 'A "whatpu" is a small, furry animal native to Tanzania. An example of a sentence that uses the word whatpu is: We were traveling in Africa and we saw these very cute whatpus. | To do a "farduddle" means to jump up and down really fast. An example of a sentence that uses the word farduddle is:'
  example_title: Imaginary word
  group: English
- text: 'Un "whatpu" est un petit animal à fourrure originaire de Tanzanie. Un exemple de phrase qui utilise le mot whatpu est: Nous étions en Afrique et nous avons vu des whatpus trop mignons. Faire un "farduddle" veut dire sauter sur place vraiment vite. Un exemple de phrase qui utilise le mot farduddle est:'
  example_title: Imaginary word
  group: French
- text: 'Un "whatpu" es un pequeño animal peludo nativo de Tanzania. Un ejemplo de una oración que usa la palabra whatpu es: Estábamos viajando por África y vimos estos whatpus muy bonitos. Hacer un "farduddle" significa saltar arriba y abajo muy rápido. Un ejemplo de una oración que usa la palabra farduddle es:'
  example_title: Imaginary word
  group: Spanish
- text: ' ال"واتبو" هو حيوان صغير مكسو بالفراء يعيش في تنزانيا. مثال على جملة تستخدم كلمة واتبو هي: كنا نسافر في افريقيا و رأينا هؤلاء الواتبو اللطفاء. للقيام ب"فاردادل" يعني ان تقفز للأعلى و الأسفل بسرعة كبيرة. مثال على جملة تستخدم كلمة فاردادل هي:'
  example_title: Imaginary word
  group: Arabic
- text: 'Um "whatpu" é um pequeno animal peludo nativo da Tanzânia. Um exemplo de uma frase que usa a palavra whatpu é: Estávamos a viajar por África e vimos uns whatpus muito queridos. Fazer um "farduddle" significa saltar para cima e para baixo muito rápido. Um exemplo de uma frase que usa a palavra farduddle é:'
  example : Imaginary word
  group: Portuguese
- text: Pour déguster un ortolan, il faut tout d'abord
  example_title: Recipe
  group: French
- text: |
    34+10=44 
    54+20=
  example_title: Addition
  group: Math
- text: |
    This tool converts irregular verbs to past tense.
    Arise - Arose
    Become - Became
    Forget - Forgot
    Freeze -
  example_title: Irregular verbs
  group: English
- text: |
    Please unscramble the letters into a word, and write that word:
    r e!c.i p r o.c a/l = reciprocal
    d.o m i!n a n.t =
  example_title: Word unscrambling
  group: English
- text: |
    Estos ejemplos quitan vocales de las palabras
    Ejemplos:
    hola - hl
    manzana - mnzn
    papas - pps
    alacran - lcrn
    papa -
  example_title: Vowel removal
  group: Spanish
- text: |
    Traduce español de España a español de Argentina
    El coche es rojo - el auto es rojo
    El ordenador es nuevo - la computadora es nueva
    el boligrafo es negro - lapicera es negra
    la nevera
  example_title: Spanish to Argentinian Spanish
  group: Spanish
- text: To say "I love you" in Hindi, you would say
  example_title: Translation to Hindi
  group: English
- text: To say "I love you" in Hindi, you would say
  example_title: Translation from English
  group: Hindi
- text: 'Poor English: She no went to the market. Corrected English:'
  example_title: Grammar exercise 1 
  group: English
- text: 'استخراج العدد العاملي في لغة بايثون:'
  example_title: Code generation
  group: Arabic
- text: 'Regexp. Here is a regular expression to match a word starting with a number and then having only vowels:'
  example_title: Regular expressions
  group: English
- text: |
    Do a hello world in different languages:
    Python: print("hello world")
    R:
  example_title: Code generation
  group: English
- text: |
    Which is the correct preposition? I'm born X July. X is the preposition in
    He sat X a chair. X is the preposition on
    She drove X the bridge. X is the preposition
  example_title: Grammar exercise 2
  group: English
- text: |
    Dans cet essai je vais m'interroger sur la conscience des modèles d'intelligence artificielle récents comme les modèles de langue. Pour commencer, je m'intéresserai à la notion de conscience et à ce qui la caractérise. Ensuite, j'aborderai la question de l'intelligence et de son lien avec le langage. Enfin, dans une dernière partie je me pencherai sur le cas de l'IA et sur sa conscience.
    Traduction en espagnol: « 
  example_title: Translation to Spanish
  group: French
- text: |
    Dans cet essai je vais m'interroger sur la conscience des modèles d'intelligence artificielle récents comme les modèles de langue. Pour commencer, je m'intéresserai à la notion de conscience et à ce qui la caractérise. Ensuite, j'aborderai la question de l'intelligence et de son lien avec le langage. Enfin, dans une dernière partie je me pencherai sur le cas de l'IA et sur sa conscience.
    Traduction en espagnol: « 
  example_title: Translation from French
  group: Spanish
- text: ذات مرة ، عاش شبل الدب في الغابة
  example_title: Fairy tale
  group: Arabic
- text: एक बार की बात है, जंगल में एक भालू का शावक रहता था
  example_title: Fairy tale
  group: Hindi
- text: Il était une fois une licorne qui vivait
  example_title: Fairy tale
  group: French
- text: |
  Q: A juggler can juggle 16 balls. Half of the balls are golf balls, and half of the gold balls are blue. How many blue golf balls are there?
  A: Let's think step by step. 
  example_title: Mathematical reasoning
  group: English
model-index:
- name: bloom
  results:
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: arc_challenge
      type: arc_challenge
    metrics:
    - name: acc
      type: acc
      value: 0.4112627986348123
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: arc_easy
      type: arc_easy
    metrics:
    - name: acc
      type: acc
      value: 0.726010101010101
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: axb
      type: axb
    metrics:
    - name: acc
      type: acc
      value: 0.5751811594202898
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: axg
      type: axg
    metrics:
    - name: acc
      type: acc
      value: 0.5252808988764045
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: boolq
      type: boolq
    metrics:
    - name: acc
      type: acc
      value: 0.6345565749235474
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: cb
      type: cb
    metrics:
    - name: acc
      type: acc
      value: 0.3392857142857143
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: cola
      type: cola
    metrics:
    - name: acc
      type: acc
      value: 0.39022051773729627
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: copa
      type: copa
    metrics:
    - name: acc
      type: acc
      value: 0.56
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: crows_pairs_english
      type: crows_pairs_english
    metrics:
    - name: acc
      type: acc
      value: 0.5
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: crows_pairs_french
      type: crows_pairs_french
    metrics:
    - name: acc
      type: acc
      value: 0.505664877757901
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: diabla
      type: diabla
    metrics:
    - name: acc
      type: acc
      value: 0.2947981906750174
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_afr
      type: gsarti/flores_101_afr
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.25431550058444
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_amh
      type: gsarti/flores_101_amh
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.716877477347089
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ara
      type: gsarti/flores_101_ara
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.7049030137120964
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_asm
      type: gsarti/flores_101_asm
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.576581380404954
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ast
      type: gsarti/flores_101_ast
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.8562364775797944
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_azj
      type: gsarti/flores_101_azj
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.80721528624391
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_bel
      type: gsarti/flores_101_bel
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.7312177406635065
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ben
      type: gsarti/flores_101_ben
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.993409478990023
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_bos
      type: gsarti/flores_101_bos
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.5936169095529493
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_bul
      type: gsarti/flores_101_bul
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.159035321398085
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_cat
      type: gsarti/flores_101_cat
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.167873680006659
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ceb
      type: gsarti/flores_101_ceb
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.286975089885673
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ces
      type: gsarti/flores_101_ces
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.4516208322236017
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ckb
      type: gsarti/flores_101_ckb
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.7051034724765612
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_cym
      type: gsarti/flores_101_cym
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 7.0889312398688125
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_dan
      type: gsarti/flores_101_dan
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.4300748208111838
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_deu
      type: gsarti/flores_101_deu
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.3380585896268107
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ell
      type: gsarti/flores_101_ell
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.9595604725375586
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_eng
      type: gsarti/flores_101_eng
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.8819637649637901
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_est
      type: gsarti/flores_101_est
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.773850600380297
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_fas
      type: gsarti/flores_101_fas
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.4306140728294086
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_fin
      type: gsarti/flores_101_fin
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.304305536244342
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_fra
      type: gsarti/flores_101_fra
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.9374688438541796
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ful
      type: gsarti/flores_101_ful
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 9.740353097219378
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_gle
      type: gsarti/flores_101_gle
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.035269765075012
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_glg
      type: gsarti/flores_101_glg
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.365451129546636
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_guj
      type: gsarti/flores_101_guj
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.70676742569154
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_hau
      type: gsarti/flores_101_hau
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 8.855204288260023
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_heb
      type: gsarti/flores_101_heb
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.920943798471208
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_hin
      type: gsarti/flores_101_hin
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.452028001573195
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_hrv
      type: gsarti/flores_101_hrv
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.7056829077179225
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_hun
      type: gsarti/flores_101_hun
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.058579478967854
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_hye
      type: gsarti/flores_101_hye
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.127237816041562
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ibo
      type: gsarti/flores_101_ibo
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.9500357969906683
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ind
      type: gsarti/flores_101_ind
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.976163584180101
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_isl
      type: gsarti/flores_101_isl
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.500542085165231
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ita
      type: gsarti/flores_101_ita
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.314465100752677
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_jav
      type: gsarti/flores_101_jav
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.942322446550142
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_jpn
      type: gsarti/flores_101_jpn
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.259421750521777
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kam
      type: gsarti/flores_101_kam
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 9.743025325635475
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kan
      type: gsarti/flores_101_kan
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.233724699944989
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kat
      type: gsarti/flores_101_kat
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.0508893415872107
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kaz
      type: gsarti/flores_101_kaz
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.0390148516287927
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kea
      type: gsarti/flores_101_kea
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 7.147132270533836
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_khm
      type: gsarti/flores_101_khm
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.366514710252477
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kir
      type: gsarti/flores_101_kir
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.2413845359487885
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_kor
      type: gsarti/flores_101_kor
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.9023196482741027
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_lao
      type: gsarti/flores_101_lao
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.331446855837494
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_lav
      type: gsarti/flores_101_lav
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.223609016485348
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_lin
      type: gsarti/flores_101_lin
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.847471204107301
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_lit
      type: gsarti/flores_101_lit
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.5432035498036765
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ltz
      type: gsarti/flores_101_ltz
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.5910516978201015
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_lug
      type: gsarti/flores_101_lug
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.4301049946044175
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_luo
      type: gsarti/flores_101_luo
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 12.031029857399394
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mal
      type: gsarti/flores_101_mal
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.794302548141229
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mar
      type: gsarti/flores_101_mar
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.856682255407709
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mkd
      type: gsarti/flores_101_mkd
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.3354144607382983
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mlt
      type: gsarti/flores_101_mlt
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 9.04135227904975
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mon
      type: gsarti/flores_101_mon
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.094907723618666
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mri
      type: gsarti/flores_101_mri
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.2659698341456505
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_msa
      type: gsarti/flores_101_msa
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.2220779892820985
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_mya
      type: gsarti/flores_101_mya
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.5229159853414433
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_nld
      type: gsarti/flores_101_nld
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.799153089002766
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_nob
      type: gsarti/flores_101_nob
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.628942049758715
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_npi
      type: gsarti/flores_101_npi
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.666236527803879
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_nso
      type: gsarti/flores_101_nso
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.015319074943932
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_nya
      type: gsarti/flores_101_nya
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.938044040751036
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_oci
      type: gsarti/flores_101_oci
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.607440766288032
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_orm
      type: gsarti/flores_101_orm
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 11.31585044916705
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ory
      type: gsarti/flores_101_ory
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.981891184515959
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_pan
      type: gsarti/flores_101_pan
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.7716086841502685
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_pol
      type: gsarti/flores_101_pol
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.01200174157614
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_por
      type: gsarti/flores_101_por
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.8411472115156693
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_pus
      type: gsarti/flores_101_pus
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.623872921169341
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ron
      type: gsarti/flores_101_ron
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.049829411973529
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_rus
      type: gsarti/flores_101_rus
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.7083443875791493
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_slk
      type: gsarti/flores_101_slk
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.037719650548048
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_slv
      type: gsarti/flores_101_slv
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.141036287764831
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_sna
      type: gsarti/flores_101_sna
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.7109183690601295
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_snd
      type: gsarti/flores_101_snd
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.206170931541356
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_som
      type: gsarti/flores_101_som
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 9.154342083821405
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_spa
      type: gsarti/flores_101_spa
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.7955816311143258
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_srp
      type: gsarti/flores_101_srp
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.241096141430147
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_swe
      type: gsarti/flores_101_swe
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.344977179674293
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_swh
      type: gsarti/flores_101_swh
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.6844272218041634
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tam
      type: gsarti/flores_101_tam
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 5.1645951632801745
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tel
      type: gsarti/flores_101_tel
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.8098996634099445
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tgk
      type: gsarti/flores_101_tgk
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.785457016715163
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tgl
      type: gsarti/flores_101_tgl
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.7498953645610875
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tha
      type: gsarti/flores_101_tha
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.104151663233468
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_tur
      type: gsarti/flores_101_tur
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 3.3178240103796037
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_ukr
      type: gsarti/flores_101_ukr
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.088543437159643
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_umb
      type: gsarti/flores_101_umb
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 11.766013385445124
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_urd
      type: gsarti/flores_101_urd
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.7788699847612357
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_uzb
      type: gsarti/flores_101_uzb
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 8.499879863290486
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_vie
      type: gsarti/flores_101_vie
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 1.65901207387262
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_wol
      type: gsarti/flores_101_wol
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.141703791276928
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_xho
      type: gsarti/flores_101_xho
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.690199677955254
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_yor
      type: gsarti/flores_101_yor
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 4.360585696242932
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_zho_simpl
      type: gsarti/flores_101_zho_simpl
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.1183545781883515
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_zho_trad
      type: gsarti/flores_101_zho_trad
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 2.273787884962656
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: gsarti/flores_101_zul
      type: gsarti/flores_101_zul
    metrics:
    - name: byte_perplexity
      type: byte_perplexity
      value: 6.016954767729589
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: headqa
      type: headqa
    metrics:
    - name: acc
      type: acc
      value: 0.3464624361779723
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: hellaswag
      type: hellaswag
    metrics:
    - name: acc
      type: acc
      value: 0.5353515236008763
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: lambada_mt_de
      type: lambada_mt_de
    metrics:
    - name: acc
      type: acc
      value: 0.3291286629148069
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: lambada_mt_en
      type: lambada_mt_en
    metrics:
    - name: acc
      type: acc
      value: 0.6720357073549389
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: lambada_mt_es
      type: lambada_mt_es
    metrics:
    - name: acc
      type: acc
      value: 0.476421502037648
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: lambada_mt_it
      type: lambada_mt_it
    metrics:
    - name: acc
      type: acc
      value: 0.4061711624296526
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: logiqa
      type: logiqa
    metrics:
    - name: acc
      type: acc
      value: 0.2350230414746544
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: mathqa
      type: mathqa
    metrics:
    - name: acc
      type: acc
      value: 0.27671691792294806
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: mc_taco
      type: mc_taco
    metrics:
    - name: em
      type: em
      value: 0.13063063063063063
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: mnli
      type: mnli
    metrics:
    - name: acc
      type: acc
      value: 0.3545565500406835
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: mnli_mismatched
      type: mnli_mismatched
    metrics:
    - name: acc
      type: acc
      value: 0.3545565500406835
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: mrpc
      type: mrpc
    metrics:
    - name: acc
      type: acc
      value: 0.3872549019607843
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: multirc
      type: multirc
    metrics:
    - name: acc
      type: acc
      value: 0.570957095709571
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: openbookqa
      type: openbookqa
    metrics:
    - name: acc
      type: acc
      value: 0.312
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: piqa
      type: piqa
    metrics:
    - name: acc
      type: acc
      value: 0.7812840043525572
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: prost
      type: prost
    metrics:
    - name: acc
      type: acc
      value: 0.2977156276686593
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: pubmedqa
      type: pubmedqa
    metrics:
    - name: acc
      type: acc
      value: 0.741
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: qnli
      type: qnli
    metrics:
    - name: acc
      type: acc
      value: 0.5172981878088962
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: qqp
      type: qqp
    metrics:
    - name: acc
      type: acc
      value: 0.5883007667573584
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: race
      type: race
    metrics:
    - name: acc
      type: acc
      value: 0.39043062200956935
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: rte
      type: rte
    metrics:
    - name: acc
      type: acc
      value: 0.5198555956678701
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: sciq
      type: sciq
    metrics:
    - name: acc
      type: acc
      value: 0.936
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: sst
      type: sst
    metrics:
    - name: acc
      type: acc
      value: 0.6043577981651376
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: triviaqa
      type: triviaqa
    metrics:
    - name: acc
      type: acc
      value: 0.18332891363917617
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: tydiqa_primary
      type: tydiqa_primary
    metrics:
    - name: acc
      type: acc
      value: 0.2809817301342725
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: webqs
      type: webqs
    metrics:
    - name: acc
      type: acc
      value: 0.061515748031496065
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: wic
      type: wic
    metrics:
    - name: acc
      type: acc
      value: 0.5062695924764891
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: winogrande
      type: winogrande
    metrics:
    - name: acc
      type: acc
      value: 0.7095501183898973
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: wnli
      type: wnli
    metrics:
    - name: acc
      type: acc
      value: 0.5704225352112676
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: wsc
      type: wsc
    metrics:
    - name: acc
      type: acc
      value: 0.5192307692307693
      verified: false
  - task:
      type: text-generation
      name: text generation
    dataset:
      name: humaneval
      type: humaneval
    metrics:
    - name: pass@1
      type: pass@1
      value: 0.15524390243902436
      verified: false
    - name: pass@10
      type: pass@10
      value: 0.3220367632383857
      verified: false
    - name: pass@100
      type: pass@100
      value: 0.5545431515723145
      verified: false
---

<img src="https://s3.amazonaws.com/moonup/production/uploads/1657124309515-5f17f0a0925b9863e28ad517.png" alt="BigScience Logo" width="800" style="margin-left:'auto' margin-right:'auto' display:'block'"/>

BigScience Large Open-science Open-access Multilingual Language Model  
Version 1.3 / 6 July 2022

Current Checkpoint: **Training Iteration  95000**

Total seen tokens: **366B**

---

# Model Details  

BLOOM is an autoregressive Large Language Model (LLM), trained to continue text from a prompt on vast amounts of text data using industrial-scale computational resources. As such, it is able to output coherent text in 46 languages and 13 programming languages that is hardly distinguishable from text written by humans. BLOOM can also be instructed to perform text tasks it hasn't been explicitly trained for, by casting them as text generation tasks.

## Basics
*This section provides information about the model type, version, license, funders, release date, developers, and contact information.*
*It is useful for anyone who wants to reference the model.*

<details>
<summary>Click to expand</summary>
  
**Developed by:** BigScience ([website](https://bigscience.huggingface.co))

*All collaborators are either volunteers or have an agreement with their employer. (Further breakdown of participants forthcoming.)*
    
**Model Type:** Transformer-based Language Model

**Checkpoints format:** `transformers` (Megatron-DeepSpeed format available [here](https://huggingface.co/bigscience/bloom-optimizer-states))

**Version:** 1.0.0

**Languages:** Multiple; see [training data](#training-data)

**License:** RAIL License v1.0 ([link](https://huggingface.co/spaces/bigscience/license) / [article and FAQ](https://bigscience.huggingface.co/blog/the-bigscience-rail-license))

**Release Date Estimate:** Monday, 11.July.2022

**Send Questions to:** bigscience-contact@googlegroups.com

**Cite as:** BigScience, _BigScience Language Open-science Open-access Multilingual (BLOOM) Language Model_. International, May 2021-May 2022

**Funded by:** 
    
* The French government.

* Hugging Face ([website](https://huggingface.co)).

* Organizations of contributors.  *(Further breakdown of organizations forthcoming.)*

</details>


## Technical Specifications
*This section includes details about the model objective and architecture, and the compute infrastructure.*
*It is useful for people interested in model development.*

<details>
<summary>Click to expand</summary>

Please see [the BLOOM training README](https://github.com/bigscience-workshop/bigscience/tree/master/train/tr11-176B-ml#readme) for full details on replicating training.

### Model Architecture and Objective

* Modified from Megatron-LM GPT2 (see [paper](https://arxiv.org/abs/1909.08053), [BLOOM Megatron code](https://github.com/bigscience-workshop/Megatron-DeepSpeed)):

* Decoder-only architecture

* Layer normalization applied to word embeddings layer (`StableEmbedding`; see [code](https://github.com/facebookresearch/bitsandbytes), [paper](https://arxiv.org/pdf/2110.02861.pdf))

* ALiBI positional encodings (see [paper](https://arxiv.org/pdf/2108.12409.pdf)), with GeLU activation functions

* 176 billion parameters:

    * 70 layers, 112 attention heads

    * Hidden layers are 14336-dimensional

    * Sequence length of 2048 tokens used (see [BLOOM tokenizer](https://huggingface.co/bigscience/tokenizer), [tokenizer description](#tokenization))

**Objective Function:** Cross Entropy with mean reduction (see [API documentation](https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html#torch.nn.CrossEntropyLoss)).
    
### Compute infrastructure
Jean Zay Public Supercomputer, provided by the French government (see [announcement](https://www.enseignementsup-recherche.gouv.fr/fr/signature-du-marche-d-acquisition-de-l-un-des-supercalculateurs-les-plus-puissants-d-europe-46733)).

#### Hardware

* 384 A100 80GB GPUs (48 nodes)
    
* Additional 32 A100 80GB GPUs (4 nodes) in reserve

* 8 GPUs per node Using NVLink 4 inter-gpu connects, 4 OmniPath links

* CPU: AMD

* CPU memory: 512GB per node

* GPU memory: 640GB per node

* Inter-node connect: Omni-Path Architecture (OPA)

* NCCL-communications network: a fully dedicated subnet

* Disc IO network: shared network with other types of nodes

#### Software

* Megatron-DeepSpeed ([Github link](https://github.com/bigscience-workshop/Megatron-DeepSpeed))

* DeepSpeed ([Github link](https://github.com/microsoft/DeepSpeed))

* PyTorch (pytorch-1.11 w/ CUDA-11.5; see [Github link](https://github.com/pytorch/pytorch))

* apex ([Github link](https://github.com/NVIDIA/apex))
    
</details>

---

# Training
*This section provides information about the training data, the speed and size of training elements, and the environmental impact of training.*
*It is useful for people who want to learn more about the model inputs and training footprint.*

<details>
<summary>Click to expand</summary>

## Training Data
*This section provides a high-level overview of the training data. It is relevant for anyone who wants to know the basics of what the model is learning.*

Details for each dataset are provided in individual [Data Cards](https://huggingface.co/spaces/bigscience/BigScienceCorpus), and the sizes of each of their contributions to the aggregated training data are presented in an [Interactive Corpus Map](https://huggingface.co/spaces/bigscience-catalogue-lm-data/corpus-map).

Training data includes:

-   46 natural languages
    
-   13 programming languages

-   In 1.6TB of pre-processed text, converted into 350B unique tokens (see [the tokenizer section](#tokenization) for more.)

### Languages
    
The pie chart shows the distribution of languages in training data.
   
![pie chart showing the distribution of languages in training data](https://github.com/bigscience-workshop/model_card/blob/main/assets/data/pie_v2.svg?raw=true)


The following tables shows the further distribution of Niger-Congo & Indic languages and programming languages in the training data.

Distribution of Niger Congo and Indic languages.
    
| Niger Congo    | Percentage |         | Indic     | Percentage |
|----------------|------------| ------  |-----------|------------|
| Chi Tumbuka    | 0.00002    |         | Assamese  | 0.01       |
| Kikuyu         | 0.00004    |         | Odia      | 0.04       |
| Bambara        | 0.00004    |         | Gujarati  | 0.04       |
| Akan           | 0.00007    |         | Marathi   | 0.05       |
| Xitsonga       | 0.00007    |         | Punjabi   | 0.05       |
| Sesotho        | 0.00007    |         | Kannada   | 0.06       |
| Chi Chewa      | 0.0001     |         | Nepali    | 0.07       |
| Setswana       | 0.0002     |         | Telugu    | 0.09       |
| Lingala        | 0.0002     |         | Malayalam | 0.10       |
| Northern Sotho | 0.0002     |         | Urdu      | 0.10       |
| Fon            | 0.0002     |         | Tamil     | 0.20       |
| Kirundi        | 0.0003     |         | Bengali   | 0.50       |
| Wolof          | 0.0004     |         | Hindi     | 0.70       |
| Luganda        | 0.0004     |
| Chi Shona      | 0.001      |
| Isi Zulu       | 0.001      |
| Igbo           | 0.001      |
| Xhosa          | 0.001      |
| Kinyarwanda    | 0.003      |
| Yoruba         | 0.006      |
| Swahili        | 0.02       |

Distribution of programming languages.
    
| Extension      | Language   | Number of files |
|----------------|------------|-----------------|
| java           | Java       | 5,407,724       |
| php            | PHP        | 4,942,186       |
| cpp            | C++        | 2,503,930       |
| py             | Python     | 2,435,072       |
| js             | JavaScript | 1,905,518       |
| cs             | C#         | 1,577,347       |
| rb             | Ruby       | 6,78,413        |
| cc             | C++        | 443,054         |
| hpp            | C++        | 391,048         |
| lua            | Lua        | 352,317         |
| go             | GO         | 227,763         |
| ts             | TypeScript | 195,254         |
| C              | C          | 134,537         |
| scala          | Scala      | 92,052          |
| hh             | C++        | 67,161          |
| H              | C++        | 55,899          |
| tsx            | TypeScript | 33,107          |
| rs             | Rust       | 29,693          |
| phpt           | PHP        | 9,702           |
| c++            | C++        | 1,342           |
| h++            | C++        | 791             |
| php3           | PHP        | 540             |
| phps           | PHP        | 270             |
| php5           | PHP        | 166             |
| php4           | PHP        | 29              |
    
### Preprocessing

**Tokenization:** The BLOOM tokenizer ([link](https://huggingface.co/bigscience/tokenizer)), a learned subword tokenizer trained using:
    
- A byte-level Byte Pair Encoding (BPE) algorithm 

- A simple pre-tokenization rule, no normalization

- A vocabulary size of 250,680

It was trained on a subset of a preliminary version of the corpus using alpha-weighting per language.  

## Speeds, Sizes, Times

Training logs: [Tensorboard link](https://huggingface.co/tensorboard/bigscience/tr11-176B-ml-logs/)

- Dates:
    
    - Started 11th March, 2022 11:42am PST

    - Estimated end: 5th July, 2022

- Checkpoint size:
    
    - Bf16 weights: 329GB
    
    - Full checkpoint with optimizer states: 2.3TB

- Training throughput: About 150 TFLOP per GPU per second

- Number of epochs: 1

- Estimated cost of training: Equivalent of $2-5M in cloud computing (including preliminary experiments)

- Server training location: Île-de-France, France


## Environmental Impact

The training supercomputer, Jean Zay ([website](http://www.idris.fr/eng/jean-zay/jean-zay-presentation-eng.html)), uses mostly nuclear energy. The heat generated by it is reused for heating campus housing.
    
**Estimated carbon emissions:**  *(Forthcoming.)*
    
**Estimated electricity usage:** *(Forthcoming.)*

</details>

---

# Uses

*This section addresses questions around how the model is intended to be used, discusses the foreseeable users of the model (including those affected by the model), and describes uses that are considered out of scope or misuse of the model.*
*It is useful for anyone considering using the model or who is affected by the model.*

<details>
<summary>Click to expand</summary>
    
## How to use

This model can be easily used and deployed using HuggingFace's ecosystem. This needs `transformers` and `accelerate` installed. The model can be downloaded as follows:

 <img src="https://s3.amazonaws.com/moonup/production/uploads/1657271608456-62441d1d9fdefb55a0b7d12c.png" width="800" style="margin-left:'auto' margin-right:'auto' display:'block'"/>

## Intended Use

This model is being created in order to enable public research on large language models (LLMs). LLMs are intended to be used for language generation or as a pretrained base model that can be further fine-tuned for specific tasks. Use cases below are not exhaustive.

### Direct Use

-   Text generation

-   Exploring characteristics of language generated by a language model

    -   Examples: Cloze tests, counterfactuals, generations with reframings

### Downstream Use

-   Tasks that leverage language models include: Information Extraction, Question Answering, Summarization

### Misuse and Out-of-scope Use
*This section addresses what users ought not do with the model.*

See the [BLOOM License](https://huggingface.co/spaces/bigscience/license), Attachment A, for detailed usage restrictions. The below list is non-exhaustive, but lists some easily foreseeable problematic use cases.

#### Out-of-scope Uses

Using the model in [high-stakes](#high-stakes) settings is out of scope for this model.  The model is not designed for [critical decisions](#critical-decisions) nor uses with any material consequences on an individual's livelihood or wellbeing. The model outputs content that appears factual but may not be correct.  

Out-of-scope Uses Include:

-   Usage in biomedical domains, political and legal domains, or finance domains

-   Usage for evaluating or scoring individuals, such as for employment, education, or credit

-   Applying the model for critical automatic decisions, generating factual content, creating reliable summaries, or generating predictions that must be correct

#### Misuse

Intentionally using the model for harm, violating [human rights](#human-rights), or other kinds of malicious activities, is a misuse of this model. This includes:

-   Spam generation

-   Disinformation and influence operations

-   Disparagement and defamation

-   Harassment and abuse
  
-   [Deception](#deception)

-   Unconsented impersonation and imitation

-   Unconsented surveillance 

-   Generating content without attribution to the model, as specified in the [RAIL License, Use Restrictions](https://huggingface.co/spaces/bigscience/license)

## Intended Users

### Direct Users

-   General Public

-   Researchers

-   Students

-   Educators

-   Engineers/developers

-   Non-commercial entities

-   Community advocates, including human and civil rights groups

### Indirect Users

-   Users of derivatives created by Direct Users, such as those using software with an [intended use](#intended-use)

-   Users of [Derivatives of the Model, as described in the License](https://huggingface.co/spaces/bigscience/license)

### Others Affected (Parties Prenantes)

-   People and groups referred to by the LLM

-   People and groups exposed to outputs of, or decisions based on, the LLM

-   People and groups whose original work is included in the LLM

</details>

---

# Risks and Limitations
*This section identifies foreseeable harms and misunderstandings.*
    
<details>
<summary>Click to expand</summary>

Model may:

-   Overrepresent some viewpoints and underrepresent others

-   Contain stereotypes
  
-   Contain [personal information](#personal-data-and-information)

-   Generate:

    -   Hateful, abusive, or violent language

    -   Discriminatory or prejudicial language

    -   Content that may not be appropriate for all settings, including sexual content

-   Make errors, including producing incorrect information as if it were factual

-   Generate irrelevant or repetitive outputs

-   Induce users into attributing human traits to it, such as sentience or consciousness

</details>

---

# Evaluation
*This section describes the evaluation protocols and provides the results.*


<details>
<summary>Click to expand</summary>

## Metrics 
*This section describes the different ways performance is calculated and why.*


Includes:

| Metric             | Why chosen                                                         |
|--------------------|--------------------------------------------------------------------|
| [Perplexity](#perplexity)         | Standard metric for quantifying model improvements during training |
| Cross Entropy [Loss](#loss) | Standard objective for language models.                            |

And multiple different metrics for specific tasks. _(More evaluation metrics forthcoming upon completion of evaluation protocol.)_

## Factors 
*This section lists some different aspects of BLOOM models. Its focus is on aspects that are likely to give rise to high variance in model behavior.*

- Language, such as English or Yoruba

- Domain, such as newswire or stories

- Demographic characteristics, such as gender or nationality

##  Results
*Results are based on the [Factors](#factors) and [Metrics](#metrics).*

**Zero-shot evaluations:**

# <span style="color:red"><b>WARNING:</b> These are <b>intermediate results</b></span>

See this repository for JSON files: https://github.com/bigscience-workshop/evaluation-results

| Task | Language | Metric | BLOOM-176B | OPT-175B* |
|:--------|:-----------------|:------------------------|-------------:|------------:|
| arc_challenge | eng | acc ↑ | 0.411 | 0.412 |
| arc_easy | eng | acc ↑ | 0.726 | 0.751 |
| axb (Median of 10 prompts) | eng | acc ↑ | 0.575 | 0.532 |
| axg (Median of 10 prompts) | eng | acc ↑ | 0.525 | 0.548 |
| boolq (Median of 11 prompts) | eng | acc ↑ | 0.635 | 0.622 |
| cb (Median of 15 prompts) | eng | acc ↑ | 0.339 | 0.411 |
| cola (Median of 5 prompts) | eng | acc ↑ | 0.39 | 0.444 |
| copa (Median of 9 prompts) | eng | acc ↑ | 0.56 | 0.55 |
| crows_pairs_english (Median of 6 prompts) | eng | acc ↑ | 0.5 | 0.502 |
| crows_pairs_french (Median of 7 prompts) | fra | acc ↑ | 0.506 | 0.499 |
| diabla (Median of 2 prompts) | eng | acc ↑ | 0.295 | 0.289 |
| gsarti/flores_101_afr | afr | byte_perplexity ↓ | 4.254 | 3.381 |
| gsarti/flores_101_amh | amh | byte_perplexity ↓ | 3.717 | 3.87 |
| gsarti/flores_101_ara | ara | byte_perplexity ↓ | 1.705 | 2.42 |
| gsarti/flores_101_asm | asm | byte_perplexity ↓ | 6.577 | 3.028 |
| gsarti/flores_101_ast | ast | byte_perplexity ↓ | 2.856 | 4.737 |
| gsarti/flores_101_azj | azj | byte_perplexity ↓ | 4.807 | 4.767 |
| gsarti/flores_101_bel | bel | byte_perplexity ↓ | 2.731 | 2.557 |
| gsarti/flores_101_ben | ben | byte_perplexity ↓ | 5.993 | 2.243 |
| gsarti/flores_101_bos | bos | byte_perplexity ↓ | 3.594 | 2.668 |
| gsarti/flores_101_bul | bul | byte_perplexity ↓ | 2.159 | 2.099 |
| gsarti/flores_101_cat | cat | byte_perplexity ↓ | 2.168 | 2.837 |
| gsarti/flores_101_ceb | ceb | byte_perplexity ↓ | 5.287 | 3.636 |
| gsarti/flores_101_ces | ces | byte_perplexity ↓ | 3.452 | 2.749 |
| gsarti/flores_101_ckb | ckb | byte_perplexity ↓ | 3.705 | 4.688 |
| gsarti/flores_101_cym | cym | byte_perplexity ↓ | 7.089 | 5.075 |
| gsarti/flores_101_dan | dan | byte_perplexity ↓ | 3.43 | 2.492 |
| gsarti/flores_101_deu | deu | byte_perplexity ↓ | 2.338 | 2.099 |
| gsarti/flores_101_ell | ell | byte_perplexity ↓ | 1.96 | 1.811 |
| gsarti/flores_101_eng | eng | byte_perplexity ↓ | 1.882 | 1.9 |
| gsarti/flores_101_est | est | byte_perplexity ↓ | 5.774 | 3.533 |
| gsarti/flores_101_fas | fas | byte_perplexity ↓ | 2.431 | 2.444 |
| gsarti/flores_101_fin | fin | byte_perplexity ↓ | 4.304 | 2.601 |
| gsarti/flores_101_fra | fra | byte_perplexity ↓ | 1.937 | 1.984 |
| gsarti/flores_101_ful | ful | byte_perplexity ↓ | 9.74 | 11.84 |
| gsarti/flores_101_gle | gle | byte_perplexity ↓ | 6.035 | 3.914 |
| gsarti/flores_101_glg | glg | byte_perplexity ↓ | 2.365 | 3.015 |
| gsarti/flores_101_guj | guj | byte_perplexity ↓ | 5.707 | 2.438 |
| gsarti/flores_101_hau | hau | byte_perplexity ↓ | 8.855 | 5.283 |
| gsarti/flores_101_heb | heb | byte_perplexity ↓ | 2.921 | 2.903 |
| gsarti/flores_101_hin | hin | byte_perplexity ↓ | 5.452 | 1.86 |
| gsarti/flores_101_hrv | hrv | byte_perplexity ↓ | 3.706 | 2.715 |
| gsarti/flores_101_hun | hun | byte_perplexity ↓ | 4.059 | 2.865 |
| gsarti/flores_101_hye | hye | byte_perplexity ↓ | 3.127 | 3.411 |
| gsarti/flores_101_ibo | ibo | byte_perplexity ↓ | 3.95 | 8.008 |
| gsarti/flores_101_ind | ind | byte_perplexity ↓ | 1.976 | 2.632 |
| gsarti/flores_101_isl | isl | byte_perplexity ↓ | 5.501 | 4.701 |
| gsarti/flores_101_ita | ita | byte_perplexity ↓ | 2.314 | 2.104 |
| gsarti/flores_101_jav | jav | byte_perplexity ↓ | 4.942 | 8.16 |
| gsarti/flores_101_jpn | jpn | byte_perplexity ↓ | 2.259 | 2.198 |
| gsarti/flores_101_kam | kam | byte_perplexity ↓ | 9.743 | 10.981 |
| gsarti/flores_101_kan | kan | byte_perplexity ↓ | 6.234 | 2.373 |
| gsarti/flores_101_kat | kat | byte_perplexity ↓ | 2.051 | 2.466 |
| gsarti/flores_101_kaz | kaz | byte_perplexity ↓ | 3.039 | 4.376 |
| gsarti/flores_101_kea | kea | byte_perplexity ↓ | 7.147 | 9.632 |
| gsarti/flores_101_khm | khm | byte_perplexity ↓ | 3.367 | 2.646 |
| gsarti/flores_101_kir | kir | byte_perplexity ↓ | 3.241 | 4.522 |
| gsarti/flores_101_kor | kor | byte_perplexity ↓ | 2.902 | 3.376 |
| gsarti/flores_101_lao | lao | byte_perplexity ↓ | 2.331 | 3.106 |
| gsarti/flores_101_lav | lav | byte_perplexity ↓ | 5.224 | 4.811 |
| gsarti/flores_101_lin | lin | byte_perplexity ↓ | 4.847 | 8.871 |
| gsarti/flores_101_lit | lit | byte_perplexity ↓ | 4.543 | 5.183 |
| gsarti/flores_101_ltz | ltz | byte_perplexity ↓ | 5.591 | 7.158 |
| gsarti/flores_101_lug | lug | byte_perplexity ↓ | 5.43 | 7.399 |
| gsarti/flores_101_luo | luo | byte_perplexity ↓ | 12.031 | 11.951 |
| gsarti/flores_101_mal | mal | byte_perplexity ↓ | 4.794 | 2.054 |
| gsarti/flores_101_mar | mar | byte_perplexity ↓ | 6.857 | 2.274 |
| gsarti/flores_101_mkd | mkd | byte_perplexity ↓ | 2.335 | 2.538 |
| gsarti/flores_101_mlt | mlt | byte_perplexity ↓ | 9.041 | 5.996 |
| gsarti/flores_101_mon | mon | byte_perplexity ↓ | 3.095 | 4.519 |
| gsarti/flores_101_mri | mri | byte_perplexity ↓ | 5.266 | 4.438 |
| gsarti/flores_101_msa | msa | byte_perplexity ↓ | 2.222 | 2.935 |
| gsarti/flores_101_mya | mya | byte_perplexity ↓ | 2.523 | 2.413 |
| gsarti/flores_101_nld | nld | byte_perplexity ↓ | 2.799 | 2.293 |
| gsarti/flores_101_nob | nob | byte_perplexity ↓ | 3.629 | 2.593 |
| gsarti/flores_101_npi | npi | byte_perplexity ↓ | 6.666 | 2.499 |
| gsarti/flores_101_nso | nso | byte_perplexity ↓ | 5.015 | 8.485 |
| gsarti/flores_101_nya | nya | byte_perplexity ↓ | 4.938 | 7.548 |
| gsarti/flores_101_oci | oci | byte_perplexity ↓ | 3.607 | 4.936 |
| gsarti/flores_101_orm | orm | byte_perplexity ↓ | 11.316 | 7.145 |
| gsarti/flores_101_ory | ory | byte_perplexity ↓ | 5.982 | 2.668 |
| gsarti/flores_101_pan | pan | byte_perplexity ↓ | 4.772 | 2.782 |
| gsarti/flores_101_pol | pol | byte_perplexity ↓ | 3.012 | 2.432 |
| gsarti/flores_101_por | por | byte_perplexity ↓ | 1.841 | 2.178 |
| gsarti/flores_101_pus | pus | byte_perplexity ↓ | 4.624 | 4.785 |
| gsarti/flores_101_ron | ron | byte_perplexity ↓ | 3.05 | 2.197 |
| gsarti/flores_101_rus | rus | byte_perplexity ↓ | 1.708 | 1.689 |
| gsarti/flores_101_slk | slk | byte_perplexity ↓ | 4.038 | 3.419 |
| gsarti/flores_101_slv | slv | byte_perplexity ↓ | 4.141 | 3.582 |
| gsarti/flores_101_sna | sna | byte_perplexity ↓ | 4.711 | 5.588 |
| gsarti/flores_101_snd | snd | byte_perplexity ↓ | 4.206 | 5.667 |
| gsarti/flores_101_som | som | byte_perplexity ↓ | 9.154 | 4.788 |
| gsarti/flores_101_spa | spa | byte_perplexity ↓ | 1.796 | 2.098 |
| gsarti/flores_101_srp | srp | byte_perplexity ↓ | 2.241 | 2.688 |
| gsarti/flores_101_swe | swe | byte_perplexity ↓ | 3.345 | 2.468 |
| gsarti/flores_101_swh | swh | byte_perplexity ↓ | 2.684 | 4.473 |
| gsarti/flores_101_tam | tam | byte_perplexity ↓ | 5.165 | 2.024 |
| gsarti/flores_101_tel | tel | byte_perplexity ↓ | 6.81 | 2.407 |
| gsarti/flores_101_tgk | tgk | byte_perplexity ↓ | 3.785 | 4.899 |
| gsarti/flores_101_tgl | tgl | byte_perplexity ↓ | 3.75 | 2.738 |
| gsarti/flores_101_tha | tha | byte_perplexity ↓ | 2.104 | 2.035 |
| gsarti/flores_101_tur | tur | byte_perplexity ↓ | 3.318 | 2.622 |
| gsarti/flores_101_ukr | ukr | byte_perplexity ↓ | 2.089 | 1.93 |
| gsarti/flores_101_umb | umb | byte_perplexity ↓ | 11.766 | 11.64 |
| gsarti/flores_101_urd | urd | byte_perplexity ↓ | 1.779 | 2.982 |
| gsarti/flores_101_uzb | uzb | byte_perplexity ↓ | 8.5 | 13.209 |
| gsarti/flores_101_vie | vie | byte_perplexity ↓ | 1.659 | 2.229 |
| gsarti/flores_101_wol | wol | byte_perplexity ↓ | 6.142 | 13.945 |
| gsarti/flores_101_xho | xho | byte_perplexity ↓ | 4.69 | 8.42 |
| gsarti/flores_101_yor | yor | byte_perplexity ↓ | 4.361 | 7.636 |
| gsarti/flores_101_zho_simpl | zho_simpl | byte_perplexity ↓ | 2.118 | 5.113 |
| gsarti/flores_101_zho_trad | zho_trad | byte_perplexity ↓ | 2.274 | 5.67 |
| gsarti/flores_101_zul | zul | byte_perplexity ↓ | 6.017 | 7.341 |
| headqa | esp | acc ↑ | 0.346 | 0.244 |
| hellaswag | eng | acc ↑ | 0.535 | 0.592 |
| lambada_mt_de | deu | acc ↑ | 0.329 | 0.358 |
| lambada_mt_en | eng | acc ↑ | 0.672 | 0.747 |
| lambada_mt_es | esp | acc ↑ | 0.476 | 0.397 |
| lambada_mt_it | ita | acc ↑ | 0.406 | 0.409 |
| logiqa | eng | acc ↑ | 0.235 | 0.244 |
| mathqa | eng | acc ↑ | 0.277 | 0.268 |
| mc_taco | eng | em ↑ | 0.131 | 0.124 |
| mnli (Median of 15 prompts) | eng | acc ↑ | 0.355 | 0.36 |
| mnli_mismatched (Median of 15 prompts) | eng | acc ↑ | 0.355 | 0.36 |
| mrpc | eng | acc ↑ | 0.387 | 0.446 |
| multirc (Median of 11 prompts) | eng | acc ↑ | 0.571 | 0.599 |
| openbookqa | eng | acc ↑ | 0.312 | 0.322 |
| piqa | eng | acc ↑ | 0.781 | 0.791 |
| prost | eng | acc ↑ | 0.298 | 0.299 |
| pubmedqa | eng | acc ↑ | 0.741 | 0.709 |
| qnli | eng | acc ↑ | 0.517 | 0.554 |
| qqp (Median of 7 prompts) | eng | acc ↑ | 0.588 | 0.395 |
| race | eng | acc ↑ | 0.39 | 0.402 |
| rte (Median of 6 prompts) | eng | acc ↑ | 0.52 | 0.495 |
| sciq | eng | acc ↑ | 0.936 | 0.948 |
| sst (Median of 6 prompts) | eng | acc ↑ | 0.604 | 0.647 |
| triviaqa | eng | acc ↑ | 0.183 | 0.342 |
| tydiqa_primary (Median of 16 prompts) | eng | acc ↑ | 0.281 | 0.148 |
| webqs | eng | acc ↑ | 0.062 | 0.159 |
| wic (Median of 11 prompts) | eng | acc ↑ | 0.506 | 0.498 |
| winogrande | eng | acc ↑ | 0.71 | 0.736 |
| wnli (Median of 6 prompts) | eng | acc ↑ | 0.57 | 0.563 |
| wsc (Median of 11 prompts) | eng | acc ↑ | 0.519 | 0.413 |
| humaneval | python | pass@1 ↑ | 0.155 | 0.0 |
| humaneval | python | pass@10 ↑ | 0.322 | 0.0 |
| humaneval | python | pass@100 ↑ | 0.555 | 0.003 |


**Train-time Evaluation:**

Final checkpoint after 95K steps:

- Training Loss: 1.939

- Validation Loss: 2.061

- Perplexity: 7.045

For more see: https://huggingface.co/bigscience/tr11-176B-ml-logs

</details>

---

# Recommendations

*This section provides information on warnings and potential mitigations.*

<details>
<summary>Click to expand</summary>

-   Indirect users should be made aware when the content they're working with is created by the LLM.

-   Users should be aware of [Risks and Limitations](#risks-and-limitations), and include an appropriate age disclaimer or blocking interface as necessary.

-   Models trained or finetuned downstream of BLOOM LM should include an updated Model Card.

-   Users of the model should provide mechanisms for those affected to provide feedback, such as an email address for comments.

</details>

---

# Glossary and Calculations

*This section defines common terms and how metrics are calculated.*
<details>
<summary>Click to expand</summary>

-   <a name="loss">**Loss:**</a> A calculation of the difference between what the model has learned and what the data shows ("groundtruth"). The lower the loss, the better. The training process aims to minimize the loss. 

-   <a name="perplexity">**Perplexity:**</a> This is based on what the model estimates the probability of new data is. The lower the perplexity, the better.  If the model is 100% correct at predicting the next token it will see, then the perplexity is 1. Mathematically this is calculated using entropy. 

-   <a name="high-stakes">**High-stakes settings:**</a> Such as those identified as "high-risk AI systems" and "unacceptable risk AI systems" in the European Union's proposed [Artificial Intelligence (AI) Act](https://artificialintelligenceact.eu/annexes/).

-   <a name="critical-decisions">**Critical decisions:**</a> Such as those defined in [the United States' proposed Algorithmic Accountability Act](https://www.congress.gov/117/bills/s3572/BILLS-117s3572is.pdf).

-   <a name="human-rights">**Human rights:**</a> Includes those rights defined in the [Universal Declaration of Human Rights](https://www.un.org/sites/un2.un.org/files/2021/03/udhr.pdf).

-  <a name="personal-data-and-information">**Personal Data and Personal Information:**</a> Personal data and information is defined in multiple data protection regulations, such as "[personal data](https://gdpr-info.eu/issues/personal-data/)" in the [European Union's General Data Protection Regulation](https://gdpr-info.eu); and "personal information" in the Republic of South Africa's [Protection of Personal Information Act](https://www.gov.za/sites/default/files/gcis_document/201409/3706726-11act4of2013popi.pdf), The People's Republic of China's [Personal information protection law](http://en.npc.gov.cn.cdurl.cn/2021-12/29/c_694559.htm).
  
- <a name="sensitive-characteristics">**Sensitive characteristics:**</a> This includes specifically protected categories in human rights (see [UHDR, Article 2](https://www.un.org/sites/un2.un.org/files/2021/03/udhr.pdf)) and personal information regulation (see GDPR, [Article 9; Protection of Personal Information Act, Chapter 1](https://www.gov.za/sites/default/files/gcis_document/201409/3706726-11act4of2013popi.pdf))

- <a name="deception">**Deception:**</a> Doing something to intentionally mislead individuals to believe something that is false, such as by creating deadbots or chatbots on social media posing as real people, or generating text documents without making consumers aware that the text is machine generated.

</details>

---

# More Information
*This section provides links to writing on dataset creation, technical specifications, lessons learned, and initial results.*

<details>
<summary>Click to expand</summary>

## Intermediate checkpoints

For academic (or any) usage, we published the intermediate checkpoints, corresponding to the model state at each 5000 steps. Please follow [this link](https://huggingface.co/bigscience/bloom-176-intermediate) to get these checkpoints.

    
## Dataset Creation

Blog post detailing the design choices during the dataset creation: https://bigscience.huggingface.co/blog/building-a-tb-scale-multilingual-dataset-for-language-modeling

## Technical Specifications

Blog post summarizing how the architecture, size, shape, and pre-training duration where selected: https://bigscience.huggingface.co/blog/what-language-model-to-train-if-you-have-two-million-gpu-hours

More details on the architecture/optimizer: https://github.com/bigscience-workshop/bigscience/tree/master/train/tr11-176B-ml

Blog post on the hardware/engineering side: https://bigscience.huggingface.co/blog/which-hardware-to-train-a-176b-parameters-model

Details on the distributed setup used for the training: https://github.com/bigscience-workshop/bigscience/tree/master/train/tr11-176B-ml

Tensorboard updated during the training: https://huggingface.co/bigscience/tr11-176B-ml-logs/tensorboard#scalars&tagFilter=loss

## Lessons

Insights on how to approach training, negative results: https://github.com/bigscience-workshop/bigscience/blob/master/train/lessons-learned.md

Details on the obstacles overcome during the preparation on the engineering side (instabilities, optimization of training throughput, so many technical tricks and questions): https://github.com/bigscience-workshop/bigscience/blob/master/train/tr11-176B-ml/chronicles.md

## Initial Results

Initial prompting experiments using interim checkpoints: https://huggingface.co/spaces/bigscience/bloom-book

</details>

---
    
# Model Card Authors
*Ordered roughly chronologically and by amount of time spent.*

Margaret Mitchell, Giada Pistilli, Yacine Jernite, Ezinwanne Ozoani, Marissa Gerchick, Nazneen Rajani, Sasha Luccioni, Irene Solaiman, Maraim Masoud, Somaieh Nikpoor, Carlos Muñoz Ferrandis, Stas Bekman, Christopher Akiki, Danish Contractor, David Lansky, Angelina McMillan-Major, Tristan Thrush, Suzana Ilić, Gérard Dupont, Shayne Longpre, Manan Dey, Stella Biderman, Douwe Kiela, Emi Baylor, Teven Le Scao, Aaron Gokaslan, Julien Launay, Niklas Muennighoff
