# Midjourney Cheatsheet 
`Midjourney for Beginners` `How-to Create Art on Midjourney` `Midjourney Cheatsheet` `GenAI Art`

## Midjourney Commands and Prompts Cheatsheet for Beginners

### Basic Prompt Anatomy: 

`/imagine prompt:` `[PREFIX]` `[SCENE]` `[SUFFIX]` `--[Parameters]`  
  
  - `PREFIX`: defines image medium & style.
  - `SCENE`: define the content.
  - `SUFFIX`: controls influence of Prefix & Scene

> NOTE: Categories overlap*

---

### Commands and Prompts Examples
---    

#### Bot Commands    

```

/blend
/describe
/fast (=toggle fast mode, jobs bill at higher rate)
    /relax (=toggle free mode, longer to generate)
/help (=info about the Midjourney bot)
/imagine (= create art e.g. /imagine waffles and pancakes)
/info (=show account info & queued jobs)
/private (=your jobs are private)
/public (=your jobs are public)        
/settings (=change bot settings)
/subscribe (=change subscription plan)
/shorten
/show <jobid> (=revive any job)
/stealth & /public (=toggle stealth mode)    

```
---

#### Weights:    

```

/imagine prompt:       hot dog
                       hot:: dog
                       hot::2 dog

```
---

#### Optional Commands:    

```
/prefer option set [NAME OF OPTION] [VALUE]
  ... e.g:
  ->     /prefer option set mycoolpreset dadaism --c 80
         ...now
         /imagine prompt: an astronaut, --mycoolpreset
         ...becomes
         /imagine prompt: an astronaut, dadaism --c 80

/prefer option set mycoolpreset
     ...deletes mycoolpreset!
/prefer option list
     ... shows presets
/prefer option remix
     ... toggles remix mode
/prefer suffix
     ... suffix to add to the end of every prompt
/prefer auto_dm
     ... automatically send DM when jobs complete
/prefer variability
     ... toggle variability mode

````
---

### Advanced Commands    

##### Using Curly Brackets `{Curly Brackets}`

```

/imagine prompt: cinematic shot of astronaut on {horse, turtle} --c {20,80}
...gets translated into four prompts:
->   cinematic shot of astronaut on a horse --c 20
     cinematic shot of astronaut on a turtle --c 20
     cinematic shot of astronaut on a horse --c 80
     cinematic shot of astronaut on a turtle --c 80  

```

#### Niji Parameters Anime Trained Model:

```

--niji / --niji 5     (anime trained model)
Niji Style Options:
--style cute
--style expressive
--style sceenic
--style original

```
---

#### Basic Parameters For Experienced Users:    

```

--ar [WIDTH:HEIGHT]   (=aspect ratio)
--c [0-100]           (=chaos, unusual results)
--q [.25|.5|1]        (=quality/time spent generating the image, 1=default)
--seed [0-4294967295] (=starting point for initial grid)
--stop [10-100]       (=stop at earlier percentage)
--s [0-1000]          (=stylize, artistic interpretation)
--tile                (=seamless patterns)
--iw [W]              (=sets image weight to W)
--no [X]              (=gives X a negative weight of -0.5)
--repeat [N]          (=repeat prompt N-times)
--video               (=create movie of image generation)

````
---

#### Version Parameters:

```
--v [1,2,3,4,5,5.1,5.2] (=model version)
--style raw             (artistic fine-tuning for V5.1 & V5.2)
--style [4a, 4b, 4c]    (artistic fine-tuning for V4)
--test, --testp, --creative (=test models, legacy)
```
---


##### Helpful Links & References

###### AI Art Creation
- [Midjourney](https://midjourney.com)
- [Discord](https://discord.com "@staysintrouble")
- [SoulGen.ai](https://www.soulgen.ai/)
- [ChatGPT](https://chat.openai.com)
- [Adobe Free BackGround Remover](https://www.adobe.com/express/feature/image/remove-background)
- [Google Keep](https://keep.google.com)
- - [Write Sonic](https://app.writesonic.com/signup?via=leverageai)    
---

###### Free Online Tools
- [Free AI Image Enhancer](https://www.stickermule.com/upscale "Stickermule is an online product site for tees, stickers, mugs, etc")
- [Free Snippet Tool for Cartoon Character Development: Figma](https://www.figma.com/)
- [Free Image Compression](https://squoosh.app/)
- [Hero.Page | Prompt Generator](https://hero.page/blog/chatgpt-and-midjourney-prompt-generator "Generate, Save & Share dynamic prompts in unlimited Lists and Spaces")
- 
---

###### Guides
- [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github "Markdown Guide")
    - [Advanced Writing Formats](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)
---

##### Origastock
- [Main](https://www.origastock.com/midjourney-ai/midjourney-styles-library.html)
  - [Midjourney Pixar Styles](https://www.origastock.com/midjourney-ai/pixar-midjourney-styles.html)
  - [Midjourney Perspective](https://www.origastock.com/midjourney-ai/perspective.html)
  - [Midjourney Themes](https://www.origastock.com/midjourney-ai/themes.html)
---
  
##### Followchain
- [List of Midjourney Commands](https://www.followchain.org/midjourney-commands/)
- [Advanced Midjourney Prompts](https://wgmimedia.com/how-to-use-midjourney-advanced-midjourney-prompts/#:~:text=Simply%20type%20%E2%80%9C/prefer%20option%20set%E2%80%9D.%20Add%20the,type%20in%20your%20prompt%20as%20the%20value.)

#### Tokenized    
- [Midjourney Guide](https://tokenizedhq.com/midjourney/)    
- [How to Use Multiple Characters in Midjourney](https://tokenizedhq.com/multiple-characters-in-midjourney/)

#### My Midjourney Wiki
- [Wiki Home](https://github.com/cbpoole/midjourney-commands-and-prompts-cheatsheet/wiki)
    - [Kid's Books](https://github.com/cbpoole/midjourney-commands-and-prompts-cheatsheet/wiki/Kids-Books)
        - [Spirit of Shiloh](https://github.com/cbpoole/midjourney-commands-and-prompts-cheatsheet/wiki/Spirit-of-Shiloh)
            - [Storyboard](https://github.com/cbpoole/midjourney-commands-and-prompts-cheatsheet/wiki/Storyboard-Vol-1)
    - [Coloring Books](xxx)

---


