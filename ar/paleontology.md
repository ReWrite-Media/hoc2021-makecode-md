### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Paleontology Puzzle

## Step 1
تمت إزالة بعض العظام من هيكل الديناصور واستبدالها. قم ببرمجة الروبوت لتدمير البلوكات الأربعة البرتقالية ووضع `كتلة العظام` التي قدمناها له.
#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||`` لتحريك الروبوت، ثم استخدم  ``||agent:وكيل يدمر||`` في الاتجاه الذي ترغب في تدمير البلوكات البرتقالية فيه، ثم استخدم  ``||agent:وكيل يضع||`` لوضع`كتلة العظام` التي قدمناها للروبوت. كرر هذه العملية حتى يتم وضع العدد المطلوب من البلوكات.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
 
