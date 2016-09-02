---
title: Typography examples
---

{% include metadata %}

# Typography examples
{:.no_toc title="Typography examples"}

*	Jekyll will generate a list of page headings here. Delete this one-item list (and the {:toc} that follows it) if you don't want it.
{:toc}

This chapter simply includes lots of examples of our workflow's default typography using the Classic theme.

This is a regular paragraph. If it follows a heading, list, definition list, blockquote or iframe, it'll be flush left (not indented). If you're looking at the HTML, ebook or print version, you should also check out the underlying markdown version, to see how to control styles with simple, plain-text formatting. There is more detail in the workflow's [README](https://github.com/electricbookworks/electric-book-workflow). 

In the markdown source of this chapter, note the `chapter` style in the markdown version's YAML header – at the top of the document. That's important: it tells the stylesheet what part of the book this is.

## Better than lorem ipsum

Who needs lorem ipsum when you can read the real thing? Here's some [Cicero translated by E. S. Shuckburgh](http://www.gutenberg.org/cache/epub/2812/pg2812.txt).

### To Terentia, Tulliola, and Young Cicero (at Rome) 

To get all small caps, wrap the text in asterisks, tagged `{:.allsmallcaps}`
{:.sidenote}

*BRUNDISIUM, 29 APRIL*{:.allsmallcaps}—Yes, I do write to you less often than I might, because, though I am always wretched, yet when I write to you or read a letter from you, I am in such floods of tears that I cannot endure it. Oh, that I had clung less to life![^1] I should at least never have known real sorrow, or not much of it, in my life. Yet if fortune has reserved for me any hope of recovering at any time any position again, I was not utterly wrong to do so: if these miseries are to be permanent, I only wish, my dear, to see you as soon as possible and to die in your arms, since neither gods, whom you have worshipped with such pure devotion, nor men, whom I have ever served, have made us any return.

[^1]: This is an endnote. Notes created like this follow [kramdown's footnote syntax](http://kramdown.gettalong.org/syntax.html#footnotes) (kramdown uses the term footnote to refer to endnotes, unfortunately).

> This is a blockquote tagged as a `{:.pull-quote}` – that's&nbsp;useful.
{:.pullquote}

I only wish, my dear, to see you as soon as possible and to die in your arms.

I have been thirteen days at Brundisium in the house of M. Laenius Flaccus, a very excellent man, who has despised the risk to his fortunes and civil existence in comparison to keeping me safe, nor has been induced by the penalty of a most iniquitous law to refuse me the rights and good offices of hospitality and friendship.[^3] May I sometime have the opportunity of repaying him! Feel gratitude I always shall. I set out from Brundisium on the 29th of April, and intend going through Macedonia to Cyzicus. 

[^3]: This is another endnote. Note how kramdown automatically numbers the these correctly, even when the markdown doesn't. The reference is designed to appear superscript. We can also do subscript in markdown, like H<sub>2</sub>0, but we have to use HTML `<sub>` tags. Our workflow doesn't yet handle complex maths by default, but it may in future, using [MathJax](http://kramdown.gettalong.org/math_engine/mathjax.html).

What a fall! What a disaster! What can I say? Should I ask you to come--a woman of weak health and broken spirit? Should I refrain from asking you? Am I to be without you, then? 

> This is a blockquote tagged as a `{:.box}` and placed at the bottom of the page (in print output) with `.float-bottom`. 
> 
> I think the best course is this: if there is any hope of my restoration, stay to promote it and push the thing on.
> 
> But if, as I fear, it proves hopeless, pray come to me by any means in your power. Be sure of this, that if I have you I shall not think myself wholly lost. 
{:.box .float-bottom}

But what is to become of my darling Tullia? You must see to that now: I can think of nothing. But certainly, however things turn out, we must do everything to promote that poor little girl's married happiness and reputation. Again, what is my boy Cicero to do? Let him, at any rate, be ever in my bosom and in my arms. 

> This is a regular blockquote. I can't write more. A fit of weeping hinders me. I don't know how you have got on; whether you are left in possession of anything, or have been, as I fear, entirely plundered. Piso, as you say, I hope will always be our friend. 

As to the manumission of the slaves you need not be uneasy. To begin with, the promise made to yours was that you would treat them according as each severally deserved. So far Orpheus has behaved well, besides him no one very markedly so. With the rest of the slaves the arrangement is that, if my property is forfeited, they should become my freedmen, supposing them to be able to maintain at law that status. But if my property remained in my ownership, they were to continue slaves, with the exception of a very few. But these are trifles. 

See the workflow [README](https://github.com/electricbookworks/electric-book-workflow#the-ebw-book-workflow) on how to embed video. This paragraph and the video won't appear in the print edition.
{:.non-printing}

{% include youtube id="KuuLhizAqo8" %}

To return to your advice, that I should keep up my courage and not give up hope of recovering my position, I only wish that there were any good grounds for entertaining such a hope. As it is, when, alas! shall I get a letter from you? Who will bring it me? I would have waited for it at Brundisium, but the sailors would not allow it, being unwilling to lose a favourable wind. 

For the rest, put as dignified a face on the matter as you can, my dear Terentia. Our life is over: we have had our day: it is not any fault of ours that has ruined us, but our virtue. I have made no false step, except in not losing my life when I lost my honours. But since our children preferred my living, let us bear everything else, however intolerable. And yet I, who encourage you, cannot encourage myself. 

If you want to start a new section of paragraphs, with space above and no indent, tag the paragraph with `{:.first}` in the markdown, like this one. I have sent that faithful fellow Clodius Philhetaerus home, because he was hampered with weakness of the eyes. Sallustius seems likely to outdo everybody in his attentions. Pescennius is exceedingly kind to me; and I have hopes that he will always be attentive to you. Sicca had said that he would accompany me; but he has left Brundisium. 
{:.first}

Take the greatest care of your health, and believe me that I am more affected by your distress than my own. My dear Terentia, most faithful and best of wives, and my darling little daughter, and that last hope of my race, Cicero, good-bye! 

A valediction, 29 April, from Brundisium
{:.valediction}

## Still better than lorem ipsum

Here's some more [Cicero translated by E. S. Shuckburgh](http://www.gutenberg.org/cache/epub/2812/pg2812.txt).

### To his Brother Quintus (in Sardinia)

*ROME, 12 FEBRUARY*{:.allsmallcaps}—I have  already told you the earlier proceedings; now let me describe what was done afterwards:

*	This is a list with a nested sublist.
*	The legations were postponed from the 1st of February to the 13th. 
*	On the former day our business was not brought to a settlement. 
*	On the 2nd of February Milo appeared for trial. 
	*	Pompey came to support him. 
	*	Marcellus spoke on being called upon by me. 
	*	We came off with flying colours. 
*	The case was adjourned to the 7th. 

Meanwhile (in the senate), the legations having been postponed to the 13th, the business of allotting the quaestors and furnishing the outfit of the praetors was brought before the house. But nothing was done, because many speeches were interposed denouncing the state of the Republic. 

*This is a sidenote in its own paragraph. It floats to the right of the paragraph it precedes.*{:.sidenote} 

Gaius Cato published his bill for the recall of Lentulus, whose son thereon put on mourning. On the 7th Milo appeared. Pompey spoke, or rather wished to speak. For as soon as he got up Clodius's ruffians raised a shout, and throughout his whole speech he was interrupted, not only by hostile cries, but by personal abuse and insulting remarks. However, when he had finished his speech—for he shewed great courage in these circumstances, he was not cowed, he said all he had to say, and at times had by his commanding presence even secured silence for his words--well, when he had finished, up got Clodius. Our party received him with such a shout—for they had determined to pay him out--that he lost all presence of mind, power of speech, or control over his countenance. 

> Here's another sidenote, but applied to a blockquote. Blockquotes as sidenotes are best if your content might be read with default browser CSS, because it keeps them distinct from the paragraph flow.
{:.sidenote}

This went on up to two o'clock -- Pompey having finished his speech at noon -- and every kind of abuse, and finally epigrams of the most outspoken indecency were uttered against Clodius and Clodia. Mad and livid with rage Clodius, in the very midst of the shouting, kept putting questions to his claque: "Who was it who was starving the commons to death?" His ruffians answered, "Pompey."
*This is a sidenote using an inline span. It's exactly aligned with its position in the source text. On screen, a browser must support CSS to float the footnote correctly, or it'll appear in the text flow.*{:.sidenote}
"Who wanted to be sent to Alexandria ?" They answered, "Pompey." "Who did they wish to go ?" They answered, "Crassus." The latter was present at the time with no friendly feelings to Milo. 

About three o clock, as though at a given signal, the Clodians began spitting at our men. 

1.	A numbered list. Kramdown will create a correctly numbered list in HTML even if the list numbers in the markdown aren't in sequence.
2.	There was an outburst of rage. 
2.	They began a movement for forcing us from our ground. 
3.	Our men charged: his ruffians turned tail. 
4.	Clodius was pushed off the rostra: and then we too made our escape for fear of mischief in the riot. 
5.	The senate was summoned into the Curia: Pompey went home. 

However, I did not myself enter the senate-house, lest I should be obliged either to refrain from speaking on matters of such gravity, or in defending Pompey (for he was being attacked by Bibulus, Curio, Favonius, and Servilius the younger) should give offence to the loyalists. 

> ![This is a figure caption](../{{ site.image-set }}/book.jpg)
>
> This is a figure caption. Formatting works *if* the image and caption are two consecutive paragraphs in a blockquote.
{:.figure}

The business was adjourned to the next day. Clodius fixed the Quirinalia (17th of February) for his prosecution. On the 8th the senate met in the temple of Apollo, that Pompey might attend. Pompey made an impressive speech. 

> That day nothing was concluded. On the 9th in the temple of Apollo a degree passed the senate "that what had taken place on the 7th of February was treasonable." 
>
> On this day Cato warmly inveighed against Pompey, and throughout his speech arraigned him as though he were at the bar. He said a great deal about me, to my disgust, though it was in very laudatory terms.

When he attacked Pompey's perfidy to me, he was listened to in profound silence on the part of my enemies. Pompey answered him boldly with a palpable allusion to Crassus, and said outright that "he would take better precautions to protect his life than Africanus had done, whom C. Carbo had assassinated." 

Accordingly, important events appear to me to be in the wind. For Pompey understands what is going on, and imparts to me 

*	that plots are being formed against his life, 
*	that Gaius Cato is being supported by Crassus, 
*	that money is being supplied to Clodius, 
*	that both are backed by Crassus and Curio, as well as by Bibulus and
his other detractors,
*	that he must take extraordinary precautions to
prevent being overpowered by that demagogue--with a people all
but wholly alienated, a nobility hostile, a senate ill-affected, and
the younger men corrupt. 

So he is making his preparations and summoning men from the country. 

On his part, Clodius is rallying his gangs: a body of men is being got together for the Quirinalia. For that occasion we are considerably in a majority, owing to the forces brought up by Pompey himself: and a large contingent is expected from Picenum and Gallia, to enable us to throw out Cato's bills also about Milo and Lentulus.*This is a note that on screen will appear as a sidenote, and in print will appear at the bottom of the page. To do this, add `.bottom` to the `.sidenote` tag: `{:.sidenote .bottom}`.*{:.sidenote .bottom} 

On the 10th of February an indictment was lodged against Sestius for bribery by the informer Cn. Nerius, of the Pupinian tribe, arid on the same day by a certain M. Tullius for riot. He was ill. I went at once, as I was bound to do. to his house, and put myself wholly at his service: and that was more than people expected, who thought that I had good cause for being angry with him. 

A paragraph tagged as a `{:.box}`. The result is that my extreme kindness and grateful disposition are made manifest both to Sestius himself and to all the world, and I shall be as good as my word. But this same informer Nerius also named Cn. Lentulus Vatia and C. Cornelius to the commissioners. 
{:.box}

On the same day a decree passed the senate "that political clubs and associations should be broken up, and that a law in regard to them should be brought in, enacting that those who did not break off from them should be liable to the same penalty as those convicted of riot." 

On the 10th of February I spoke in defence of Bestia on a charge of bribery before the praetor Cn. Domitius, in the middle of the forum and in a very crowded court; and in the course of my speech I came to the incident of Sestius, after receiving many wounds in the temple of Castor, having been preserved by the aid of Bestia. Here I took occasion to pave the way beforehand for a refutation of the charges which are being got up against Sestius, and I passed a well-deserved encomium upon him with the cordial approval of everybody. He was himself very much delighted with it. I tell you this because you have often advised me in your letters to retain the friendship of Sestius. 

Sestius
:	This is an example of definition-list typography. Publius Sestius was a Roman senator in the 1st century BC. He was a praetor in 53 BC, as well as a friend and ally of Cicero, by whom he was defended in 56 BC. Upon the outbreak of Caesar's Civil War he joined the party of Pompey, having become the governor of Cilicia. According to Plutarch's Life of Brutus he was accompanied by Marcus Brutus to his province, but Sestius subsequently went over to Caesar, who sent him into Cappadocia in 48&nbsp;BC.

This is I am writing this on the 12th of February before daybreak; the day on which I am to dine with Pomponius on the occasion of his wedding. 

Our position in other respects is such as you used to cheer my despondency by telling me it would be--one of great dignity and popularity: this is a return to old times for you and me effected, my brother, by your patience, high character, loyalty, and, I may also add, your conciliatory manners. The house of Licinius, near the grove of Piso, has been taken for you. But, as I hope, in a few months time, after the 1st of July, you will move into your own. 

Note
:	You can tag almost any element with `{:.box}`, including definition lists like this.
{:.box}

Some excellent tenants, the Lamiae, have taken your house in Carinie. I have received no letter from you since the one dated Olbia. I am anxious to hear how you are and what you find to amuse you, but above all to see you yourself as soon as possible. 

Take care of your health, my dear brother, and though it is winter time, yet reflect that after all it is Sardinia that you are in. 

13 February
{:.valediction}

## Poetry

Best-practice poetry layout indents a poem till its longest line is centred on the page. To achieve this, we put the entire poem, including the title, in a 'verse' blockquote and specify how wide this poem should be on the page. 

> -	#### To One Who Has Been Long in City Pent
> -	To one who has been long in city pent,
> -	{:.indent-2}'Tis very sweet to look into the fair
> -	{:.indent-2}And open face of heaven,—to breathe a prayer
> -	Full in the smile of the blue firmament.
> -	Who is more happy, when, with heart's content,
> -	{:.indent-2}Fatigued he sinks into some pleasant lair
> -	{:.indent-2}Of wavy grass, and reads a debonair
> -	And gentle tale of love and languishment?
> -	
> -	Returning home at evening, with an ear
> -	{:.indent-2}Catching the notes of Philomel,—an eye
> -	Watching the sailing cloudlet's bright career,
> -	{:.indent-2}He mourns that day so soon has glided by:
> -	E'en like the passage of an angel's tear
> -	{:.indent-2}That falls through the clear ether silently.
> {:.verse}
{:.verse .width-90}

Here's a long poetry example.

> - #### Gerontion
> - {:.indent-1}Thou hast nor youth nor age
> - {:.indent-1}But as it were an after dinner sleep
> - {:.indent-1}Dreaming of both.
> - 
> - Here I am, an old man in a dry month,
> - Being read to by a boy, waiting for rain.
> - I was neither at the hot gates
> - Nor fought in the warm rain
> - Nor knee deep in the salt marsh, heaving a cutlass,
> - Bitten by flies, fought.
> - My house is a decayed house,
> - And the jew squats on the window sill, the owner,
> - Spawned in some estaminet of Antwerp,
> - Blistered in Brussels, patched and peeled in London.
> - The goat coughs at night in the field overhead;
> - Rocks, moss, stonecrop, iron, merds.
> - The woman keeps the kitchen, makes tea,
> - Sneezes at evening, poking the peevish gutter.
> - 
> - {:.indent-8}I an old man,
> - A dull head among windy spaces.
> - 
> - Signs are taken for wonders. "We would see a sign":
> - The word within a word, unable to speak a word,
> - Swaddled with darkness. In the juvescence of the year
> - Came Christ the tiger
> - 
> - In depraved May, dogwood and chestnut, flowering Judas,
> - To be eaten, to be divided, to be drunk
> - Among whispers; by Mr. Silvero
> - With caressing hands, at Limoges
> - Who walked all night in the next room;
> - By Hakagawa, bowing among the Titians;
> - By Madame de Tornquist, in the dark room
> - Shifting the candles; Fraulein von Kulp
> - Who turned in the hall, one hand on the door. Vacant shuttles
> - Weave the wind. I have no ghosts,
> - An old man in a draughty house
> - Under a windy knob.
> - 
> - After such knowledge, what forgiveness? Think now
> - History has many cunning passages, contrived corridors
> - And issues, deceives with whispering ambitions,
> - Guides us by vanities. Think now
> - She gives when our attention is distracted
> - And what she gives, gives with such supple confusions
> - That the giving famishes the craving. Gives too late
> - What's not believed in, or if still believed,
> - In memory only, reconsidered passion. Gives too soon
> - Into weak hands, what's thought can be dispensed with
> - Till the refusal propagates a fear. Think
> - Neither fear nor courage saves us. Unnatural vices
> - Are fathered by our heroism. Virtues
> - Are forced upon us by our impudent crimes.
> - These tears are shaken from the wrath-bearing tree.
> - 
> - The tiger springs in the new year. Us he devours. Think at last
> - We have not reached conclusion, when I
> - Stiffen in a rented house. Think at last
> - I have not made this show purposelessly
> - And it is not by any concitation
> - Of the backward devils.
> - I would meet you upon this honestly.
> - I that was near your heart was removed therefrom
> - To lose beauty in terror, terror in inquisition.
> - I have lost my passion: why should I need to keep it
> - Since what is kept must be adulterated?
> - I have lost my sight, smell, hearing, taste and touch:
> - How should I use it for your closer contact?
> - 
> - These with a thousand small deliberations
> - Protract the profit of their chilled delirium,
> - Excite the membrane, when the sense has cooled,
> - With pungent sauces, multiply variety
> - In a wilderness of mirrors. What will the spider do,
> - Suspend its operations, will the weevil
> - Delay? De Bailhache, Fresca, Mrs. Cammel, whirled
> - Beyond the circuit of the shuddering Bear
> - In fractured atoms. Gull against the wind, in the windy straits
> - Of Belle Isle, or running on the Horn,
> - White feathers in the snow, the Gulf claims,
> - And an old man driven by the Trades
> - To a sleepy corner.
> - 
> - {:.indent-8}Tenants of the house,
> - Thoughts of a dry brain in a dry season.
> {:.verse}
{:.verse}

On screen, there's a button here. This one won't show in print output because it's tagged `.non-printing`. To create a button, just add `{:.button}` directly after a link, like this: `[Go to Contents](0-3-contents.html){:.button}`.

[Go to Contents]({{ web-contents-page }}){:.button}
{:.first .non-printing}
