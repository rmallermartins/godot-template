# Godot Project Template

A Project Structure Template for Godot Games

Based on @jotson Youtube Video:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EXgyOrjLV1g" target="_blank">
    <img src="http://img.youtube.com/vi/EXgyOrjLV1g/0.jpg" alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" />
</a>

## Configuration

Change project name in [`game/project.godot`](game/project.godot) editing the line:

```properties
config/name="Godot Template"
```

## Structure

* **assets/** - *raw audio, video, images files material outside game, like blog posts*
* **build/** - *game builds*
* **game/** - *actual Godot project*
  * **entities/** - *game entities **Scenes**, like Player, Enemy*
  * **levels/** - *game levels **Scenes**, could be real levels, different areas*
  * **gui/** - *game GUI **Scenes**, buttons, labell*
  * **(add as needed)** - *The ideia of this folder level is to have big structural divisions, some examples: **systems**, **behaviors**, **commons**, ...*
  * ***(game assets)*** - *create folders next to the **Scene** that uses them: **sfx**, **texture**, ...*
* **platforms/** - *store/social media assets (banners, icons, logos)*
* **press/** - *contact info, pitches, summaries, mediakit*
* **scrapbook/** - *all screenshots and videos made*
* **scripts/** - *scripts for automating things like builds, deploys, cleanings, etc...*

> Remember this is just a helper/starter, you should change and evolve this structure as you and your project needs
