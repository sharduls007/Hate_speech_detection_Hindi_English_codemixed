# A Comparative Study of Different State-of-the-Art Hate Speech Detection Methods for Hindi-English Code-Mixed Data

If you are using the annotation guidelines mentioned on this page, then please site our paper:


    @inproceedings{rani-etal-2020-hate,
    title = "A Comparative Study of Different State-of-the-Art Hate Speech Detection Methods for Hindi-English Code-Mixed Data",
    author = "Rani, Priya and Suryawanshi, Shardul and Goswami, Koustava and Chakravarthi, Bharathi Raja and Fransen, Theodorus and McCrae, John P.,
    booktitle = "Proceedings of the Second Workshop on Trolling, Aggression and Cyberbullying ({TRAC}-2018)",
    month = May,
    year = "2020",
    publisher = "Association for Computational Linguistics",
    abstract = "Hate speech detection in  social media communication has become one of the primary concerns to avoid conflicts and curb undesired activities. In an environment where multilingual speakers switch among multiple languages, hate speech detection becomes a challenging task using methods that are designed for monolingual corpora. In our work, we attempt to analyze, detect and provide a comparative study of hate speech in a code-mixed social media text. We also provide a Hindi-English code-mixed data set consisting of Facebook and Twitter posts and comments. Our experiments show that deep learning models trained on this code-mixed corpus perform better.",}

## Annotation Guidelines

Hate Speech could be understood as any kind of linguistic behaviour, which is intended to target an individual or community and show their dissent using offensive and abusive content. The following document presents the guidelines for annotation of social media comments and posts for hate speech detection research at the Data Science Institute, National University of Ireland Galway. All the examples in this guideline are retrieved from either from Facebook or Twitter.          
The data will be annotated at the document level which means annotation will be done for the complete post, a comment, a tweet or a single unit of the discourse. The annotation will be conducted at one level. The current annotation phase consists of three round of annotation of 500 tweets per annotator in the first and second around and 2000 tweets in the third round. The goal of the annotation is to calculate inter annotator agreement and to improve the guidelines accordingly in each phase of the annotation and find the possible problems. It will be carried out using simple google forms. Each google form consists of 100 tweets.

The annotation will not require that the participants to write the tweets but the annotation will be done on the basis of tweets itself. For example : - 

    “वाराणसी: BHU में फिर एक छात्रा से छेड़छाड़  लड़की की पिटाई के बाद छीना गया मोबाइल #BHU #BHU_लाठीचार्ज #BHU_Molestation”
    A female student has been molested again in BHU. The student mobile has been snatched away after beating her.

In the example above, the tweet itself is not something that shows hate speech but the action which leads to such tweets that is BHU molestation is offensive as well as targeted towards an individual. Therefore the tweet will not be annotated with respect to the action but the tweet itself. If the tweet itself is biased and reinforces or makes use of a biased or stereotypical representation of a particular hate speech then, it should be marked as hate speech.

**Annotation Scheme**

Level 1 : Hate Speech Identification
The one and only level  is a simple binary class classification in which we  between hate speech and non-hate speech posts. The two labels used for this categorization are:
- (NOT) Not hate speech – The posts which do not contain any sort of offense or profanity either covert or overt. Examples:
    - “raise your voice louder,comrades.”
    - “ना बिटिया माफ करेगी  ना माँ गंगा... #BHU_लाठीचार्ज #bhu_molestation #BHUatJantarMantar”
    - Neither your daughter nor goddess ganga will forgive you.

- (HAT) Hate Speech – Any post which contains direct or indirect offensive language or any kind of threat. It is considered offensive in nature if it contains insults, threats, slangs, profane language and swear words within the context of the whole post. Some posts may contain covert offensive language, which is expressed through sarcasm, satire or polite expressions. Examples:
    - “teri ma ka bur chodna hai ma se puch kar bata mc me to nahi hai kyo ki bur me muh bhi lagana hai”
    - I want to fuck your mother. Ask your mother and let me know because I want to suck it as well.
    - “rssabvp vhp bajarangadal have no balls whenever bjp came to power at center laffada bjpvhp rssabvp start violence in streets colleges hotels pubs as if they komani when congress government at centre all blunder pariwar disappeared that's why they have no balls”
    - “Well, Ravish Kumar is as much a journalist as Kanhaiya is a student...what's new #ShutDownJNU ”

- If the post aimed towards the stereotypical gender roles of the victim as well as the offender. It also includes offensive references to one’s sexuality and sexual orientation. It should be marked as hate speech as these posts are targeted towards specific communities to demean them. For example:
    - "मर्द की कीमती चीज उसकी ज़ुबान होती है  सीना तो बहुत से हीजड़ो का भी 56 इंच होता है .. #BHU_लाठीचार्ज #bhu_molestation #BHUProtests”
    - The most precious thing about a man is his words, not the length of the chest as even a spado has 56’’ chest.

- Any comment / post which attacks a previous comment / post. It can be a hate speech. A couple of examples are given below.
    - Muh kala hai dogle ka dil bhi kala gaddar hai mujhe tum dikh jaye sala juta marunga dogala deshdrohi

    - This hypocrite has lost his face, his heart is also bad, as soon as I shall see you moron, will hit you with a shoe, you hypocritical anti-national

    - tera samdhi mulayam singh yadav bolta tha rape koi badi galti nahi baccho se galti ho jaati hai. phaasi ki kya jarurat hain. pravachan aur updesh khatam kaha hotey hain. 100 chuhe khaakar billa chala haj ko.

    - Your child’s father-in-law Mulayam Singh used to say that rape is not a big mistake and children make such mistakes. What is the use of hanging till death? The preaching and speech hardly ends. He is now pleading innocence after committing hundreds of crimes.
- Any post which is directed towards particular community/ ethnic minorities, is considered as hate speech. 
    - Example:अगर 370 और 35A हटी तो कश्मीरी मुसलमान कहां रहेंगे- उमर अब्दुल्ला ।    मैं बताता हूँ भोसड़ीके वो सब फिर अपनी औकात में रहेंगे ।। 
    Where will muslim live if article 370 and 35A is removed. I will tell you Crotch.
