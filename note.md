# VS Code
## Extensions
- Grammarly
- Markdown Checkbox
  - `⌘ + shift + C` - create checkbox
  - `⌘ + shift + enter` - mark checkbox done
- Markdown TOC
- Markdown+Math
- Path Intellisense
- Vim
  - setting
  - ```    
    "vim.insertModeKeyBindings": [
        {
            "before": ["j", "j"],
            "after": ["<esc>"]
        }
    ]
    ```
- Visual Studio IntelliCode

## Shortcuts
### Common
- `⌘ + shift + X` - extension
- `⌘ + KS` - list of all shortcuts
- `⌘ + P` - command palette:  
  - search for files
  - execute command
  - more...
- ``ctrl + ` `` - terminal
- `shift + option + ⬆ / ⬇` - copy current line up / down
- `⌘ + shift + ctrl + arrow left / right` - shrink / expand selection
- `⌘ + shift + F` - find text in all files, same as intellij
### Editing
- `⌥ + click` - add secondary cursor and edit multiple place at once
- `⌘ + D` - find and select next occurance
- `⌘ + ⌥ + shift ⬆ / ⬇` - add cursor to prev / next line
- `⌘ + ⌥ + [ / ]` - fold / expand blocks
### Browsing file
- `⌘ + B` - toggle left sidebar
- `⌘ + shift + E` - focus document sidebar
- `⌘ + ⬇` - open file
- `ctrl + - / _` - (go back / go forward) changed to match intellij `⌘ + [ / ]`
- `⌘ + shift + \` - jump to matching bracket

# System Design
https://github.com/yangshun/tech-interview-handbook/tree/master/experimental/design

# Algorithm

# Fastai

# Machine Learning

## Weather forecast with ai?
- use satellite image?

## NLP
### State of the art
- from [Analytic Vidhya 2019-Mar](https://www.analyticsvidhya.com/blog/2019/03/pretrained-models-get-started-nlp/):  
  - ULMFit(Universal Language Model Fine-Tuning) from fastai
  - Transformer
    - [All you need is attention](https://arxiv.org/abs/1706.03762)
    - [Universal Transformer](https://arxiv.org/pdf/1807.03819v3.pdf)
  - BERT (Google)
  - Transformer-XL (Google)
  - GPT2 (OpenAI)
  - [StanfordNLP](https://github.com/stanfordnlp/stanfordnlp) for implementations

# Quote
`It Is Our Moments Of Struggle That Define Us - Angel Gas Fallen`  
Some people also said we earn most of the money during a bear market. which kind of true in a way.
I feel more like how we deal with struggle and the low times that defines us. You gonna sink in or you gonna rebound? how deep you have to sink? It is a delicate situation that you can't sit there do nothing or flail your limbs like a mad man. It requires you to try different things and crawl out of it one step at a time. 

# Idea & problems

## How to convert this writing system to creating software?
I found this [Medium Post](https://medium.com/better-marketing/the-system-i-used-to-write-5-books-and-over-1-000-blog-posts-5872451d7461) quite inspiring. This got me into thinking how to convert this system into creating software. Always wanted to learn new things and work on side projects. But never really able to produce anything. And I really agree with this quote `The best practice is the kind done in public, and the best writing is the stuff you intend to publish.` The problem of creating software is it takes longer. Being able to iterate on the 3 step system in a few days and have a finished piece of writing must be satisfying. The long drag of learning something new and creating working software always kills the motivation for me. What to do?
1. Collect Ideas
2. Write and Save
3. Edit and Publish

## Feedback analysis
### What it does?
- Overall sentiment
- Summary / representative phrase (maybe group by sentiment level)
- Data visualization
### Problems:
- Find pre-train model that is suitable for the task
- Find data to test
- Data visualization

## Simple markdown blog
- not sure how

## Easy image selector
- took multiple similar photo
- easy side by side view to select one
- or suggesting or auto select one

## E7 / game fan art gallery
- fan art by game, by character
- reverse search find source / artist
- more like it
- annonymous feedback / summarize help people improve

# Misc
- type the command symbol ⌘: ⌘ + ctrl + space, search `place of`

# E7
## Routine 
### Daily
* [ ] Abyss
* [ ] Huche
* [ ] Labrinth
* [ ] Guild Aid
* [ ] Guild Donate
* [ ] Guild War
* [ ] Guild World Boss
* [ ] Reputation Daily
* [ ] RTA (Web Event)
* [ ] Web Event

### Weekly
* [ ] Conquest point Molagora
* [ ] Craft Charm
* [ ] Guild shop
* [ ] Hall of Trails
* [ ] Hell Raid
* [ ] Pet shop
* [ ] Transmit shop

## Flat vs percentage state
|Type|Flat|Percentage|Threshold|
|-|-|-|-|
|Attack|100|12%|833.3|
|Defence|60|12%|500|
|Health|540|12%|4500|

## Hell Raid
### Map
![map](./e7_hr_map.png =500x)

### Queen
- Need buff strip
- AOE
- 3 debuf got cleansed

Good units:
- Iseria - strip, pair well with Tamarinne
- Charles - S2 can strip buff, aoe, attack buff
- Tamarinne - cleanse, strip, heal, attack buff

Team:
|1|2|3|4|Camp| Morale|
|-|-|-|-|-|-|
|Iseria|Tamarinne|Charles|SSB|(3) Joyful Memories, (3) Dream| 27|
|Iseria|Tamarinne|Charles|Montmo| (4) Comforting, (1) Sad Memory|36|

### Arahakan
|1|2|3|4|Camp| Morale|
|-|-|-|-|-|-|
|A. Ravi|Vivian|Tamarinne|C. Zerato|(1) Myth, (2) Ctiticsim| 37 |

### Karkanis
- Strong DPS
- No earth unit

Team:
|1|2|3|4|Camp| Morale|
|-|-|-|-|-|-|
|A. Ravi|A. Montmo|Luna|C. Zerato|(1) Myth, (3) Ctiticsim| 24 |


### Vera
- Need AOE, cleanse.  
- First phrase need to clear all egg / spider. 
- Single target attack Vera without clearing minion trigger AOE counter attack that stuns.

Good units:
- C. Zerato - return debuff, immune stun
- Vivian - short cooldown AOE
- Tamarinne - cleanse and heal. element adv.

|1|2|3|4|Camp| Morale|
|-|-|-|-|-|-|
|Melissa|Vivian|Tamarinne|C. Zerato|(2) Myth, (3) Cute Cheer| 36 |

### Juleeve (Green)
- Need S1 without debuff
- Need cleanse

|1|2|3|4|Camp| Morale|
|-|-|-|-|-|-|
|A.Ravi|Luna|A. Montmo|Lilias|(1) Myth, (2) Sad memory| 16 |

## Counters
### Counter Attacker
- No Counter Skill: ML Tenebria, Pavel
- Roana

### Revive
- Extinction
- S. Angelica

### ML Ken
- B. Dingo - S3 (need sb 20) grant invincibility, attack buff and extra turn then S2 (100% crit). ML ken counter but B. Dingo is invincible. Then trigger S1
- ML Tenebria, Pavel - skill does not trigger counter
- Gunther - he just won't crit
- Rikioris - Strip 1 buff and stun all
- One-shot him - Cermia, W. Schuri, C. Dom, LQ Charlotte

### ML Vildred
- One more turn mechanic - Karin, BB Karin, 
- Extinction / No Revive - Sigret, Spez, Lilibet, S. Angelica
- CR manipulation - Lidica

### SS Bellona
- Roana - heal and cr push when countered
- ML Tenebria, Pavel - no counter
- One-shot - Lilibet, Yufine, Pavel, C. Dom, W. Schuri
- Melissa - S3 is element neutral, put curse on SSB, then S2 someone else

## Cheese
### Reflect Comp
- Composition: lv 5 Taranor Royal Guard, Domineil, ML Achates + any
- ML Achates grant immortality and Domineil cast reflect shield to TRG sit back and let the enemy hit your TGR
- Pitfall: Need 4 dps in the enemy team. If buff on TRG being stripped, you lose.

### Max Morale?
|1 |2 |3 |4 | Camp | Morale |
|-|-|-|-|-|-|
|A. Ravi|Vivian|C. Zerato| Melissa| (1) Myth, (2) Criticism| 52 |
|A. Ravi|B. Dingo |C. Zerato| Melissa| (1) Myth, (1) Heroic Tale| 48 |
|A. Ravi|Vivian|C. Zerato| B. Dingo | (1) Myth, (1) Heroic Tale| 47 |
|A. Ravi|Vivian|C. Zerato| Tamarinne| (1) Myth, (2) Criticism| 37 |
