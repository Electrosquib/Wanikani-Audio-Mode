# Wanikani Audio Mode Script
<img src="https://github.com/Electrosquib/Wanikani-Audio-Mode/blob/main/img/blurred.png" width="100px"></img>
If you wish to improve your listening skills for Japanese vocabulary while doing your regular Wanikani reviews, this script is for you. I had trouble recognizing words when listening to japanese audio, even ones I already knew. Listening to more material helps, but I wanted to incorporate it into my regular Wanikani routine to maximize time and efficiency. When this script is active, it will automatically blur out vocabulary meanings while playing Wanikani's audio for that word. This forces you to recall words just by hearing them, which I found quite humbling yet massively beneficial to my listening skills. The downside to this approach is that hearing the words being spoken makes the reading questions unnaturally easy, leading to less improvement in this area. However, I personally find the readings already much easier than meanings, especially because you can infer them by a word's kanji composition. As such, this is not a major concern for me.

## Installation 
Before installing this script, please ensure you have a userscript manager like Tampermonkey installed in your browser. This will allow the script to modify the behavior of your Wanikani review page and allow it to work. 

To install this script, go to this url: ""
Then click the install button.

## Modification
The speakers voice can be changed to male or female by modifying the "voice_actor" variable accordingly. Setting the value to 0 changes the voice to Kyoko (female), while 1 changes it to Kenichi (male). 

In the next two lines, the colors of vocabulary and kanji review text can be changed. If you have a CSS injector creating a custom theme for your Wanikani page, changing these colors to match your pallette can be done. If you use the stock Wanikani theme, leaving these values to something like #FFF is fine.
