# Hubot-celery-man

Hubot script for Celery Man from [Tim and Eric](https://www.youtube.com/watch?v=MHWBEK8w_YY)

See [`src/celery-man.coffee`](src/celery-man.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install @akitabox/hubot-celery-man --save`

Then add **hubot-celery-man** to your `external-scripts.json`:

```json
[
  "@akitabox/hubot-celery-man"
]
```

## Commands
`hubot celery man` - celery man gif

`hubot 4d3d3d3` - another gif

`hubot add sequence oyster` - respond with an image

`hubot oyster smiling` - gif

`hubot do we have any new sequences` - prompt to see gif

`hubot hat wobble` - hat wobble gif

`hubot nude tayne` - responds with not computing

`NUDE TAYNE` - responds with NSFW

## Sample Interaction

```bash
user1>> hubot celery man
hubot>> http://mlkshk.com/r/4SBP.gif
```
```bash
user1>> hubot 4d3d3d3
hubot>> 4d3d3d3 ENGAGED
hubot>> http://i.imgur.com/w1qQO.gif
```
```bash
user1>> hubot add sequence oyster
hubot>> http://i.imgur.com/EH2CJ.png
```
```bash
user1>> hubot do we have any new sequences
hubot>> I have a BETA sequence I have been working on.
hubot>> Would you like to see it?
user1>> yes
hubot>> http://i.imgur.com/h27BPKW.png
```
```bash
user1>> hubot hat wobble
hubot>> http://i.imgur.com/5kVq4.gif
```
```bash
user1>> flarhgunnstow
Hubot>> http://i.imgur.com/X0sNq.gif
```

## NPM Module

[hubot-celery-man](https://www.npmjs.com/package/@akitabox/hubot-celery-man)
