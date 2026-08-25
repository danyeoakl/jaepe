# Jaepe

Jaepe is a fan-made animated pet for Codex: a green frog caricature with a blunt black bowl cut, round glasses, a fitted black shirt, and full tattoo sleeves.

![Jaepe idle animation](assets/jaepe-idle.gif)

## Gag animation loops

| Codex state | Jaepe animation |
| --- | --- |
| `waving` | Noogie<br>![Jaepe giving a noogie](assets/jaepe-noogie.gif) |
| `jumping` | Barrel stuffing<br>![Jaepe stuffing Pepe into a barrel](assets/jaepe-barrel.gif) |
| `failed` | Straitjacketed hospital door<br>![Jaepe pushing Pepe through an institutional door](assets/jaepe-straitjacket.gif) |
| `waiting` | Discarded-bus apartment<br>![Jaepe stuffing Pepe into a bus apartment](assets/jaepe-bus.gif) |
| `review` | Censored transcript tearing<br>![Jaepe tearing a censored transcript](assets/jaepe-jjij.gif) |

## Install

Clone or download this repository, then copy the installable package into the local Codex pets directory:

```sh
mkdir -p ~/.codex/pets/jaepe
cp pet.json spritesheet.webp ~/.codex/pets/jaepe/
```

In Codex, open **Settings → Pets**, choose **Refresh**, select **Jaepe**, and wake the pet. You can also use `/pet`. See the [Codex Pets documentation](https://learn.chatgpt.com/docs/pets).

## Pet contract

- Codex pet ID: `jaepe`
- Sprite contract: v2
- Atlas: 1536 × 2288 WebP
- Grid: 8 × 11 cells at 192 × 208 pixels
- Animation: nine standard state rows, including five custom gag loops, plus 16 clockwise look directions
- SHA-256: `56fa91436ed165ec2577e298585bc7c87f37fed7b95b30c16f6ecaf02333ec61`

The complete animation and gaze checks are available in [the contact sheet](docs/contact-sheet.png) and [the direction sheet](docs/direction-sheet.png).

## Fan-art notice

This is independently generated fan art inspired by Pepe-style internet frog imagery and likeness cues associated with South Korean public figure Lee Jae-myung. It is not affiliated with or endorsed by Lee Jae-myung, any Pepe rights holder, OpenAI, or Codex. See [NOTICE.md](NOTICE.md).
