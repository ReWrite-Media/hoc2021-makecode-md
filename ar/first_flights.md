### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# First Flight

## Step 1
إحدى الطائرات الأولى على وشك الإقلاع، لكن هناك ثقوب في مدرج الطيران! قم ببرمجة الروبوت لملء هذه الثقوب باستخدام `Dirt` البلوكات التي قدمناها له.

#### ~ tutorialhint  
استخدم ``||agent:وكيل ينقل||``لترسل الروبوت إلى الحفرة. قم بملء كل حفرة باستخدام ``||agent:وكيل يضع||``إلى وضع الـ `Dirt` البلوك الذي قدمناه للروبوت. كرر. ``||agent:وكيل ينقل||`` و``||agent:وكيل يضع||`` حتى يتم ملء جميع الحفر.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```
