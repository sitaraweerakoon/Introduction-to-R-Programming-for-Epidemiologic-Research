---
title: 'Module X'
description: 'Video exercise'
free_preview: true
---

## Introduction

```yaml
type: VideoExercise
key: 55f838b3cd
lang: r
xp: 50
skills: 1
```


---

## My fake multiple choice page

```yaml
type: MultipleChoiceExercise
key: 4e72afdc13
xp: 50
```

Test multiple choice question. Blah, blah, blah

`@possible_answers`
- Yes
- [No]
- Maybe

`@hint`
Here is a hint

`@pre_exercise_code`
```{r}

```

`@sct`
```{r}
msg1 <- "Not good, try again!"
msg2 <- "Nice one!"
msg3 <- "Not quite, give it another shot."
ex() %>% check_mc(2, feedback_msgs = c(msg1, msg2, msg3))
```

---

## Sitara test

```yaml
type: VideoExercise
key: 806dc06927
xp: 50
```

`@projector_key`
fb76fe11a47e52a92601175cbbcd7ee5
