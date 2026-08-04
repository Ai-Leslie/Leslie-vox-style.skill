# Leslie-vox-style.skill

An open-source, bilingual (中文 / English) Codex skill collection for documentary
ideation, VOXSTAGE editorial paper-collage image prompts, and locked-frame animation.

## VOXSTAGE reference board

![VOXSTAGE visual reference board](assets/voxstage-reference.png)

The same reference board is embedded in every packaged skill under
`assets/voxstage-reference.png`, so each installation remains self-contained.

## Skills

1. `documentary-narrative-engine` - develop documentary topics, structure,
   narration, VOXSTAGE visual beats, and thumbnail concepts.
2. `documentary-image-prompts` - turn narration into a timed beat table and
   one editorial collage image prompt per beat.
3. `editorial-paper-collage-animation` - animate a supplied final frame as a
   ten-second handcrafted paper-collage assembly.

## Install

Copy any folder from `skills/` into your Codex skills directory:

```bash
cp -R skills/documentary-narrative-engine ~/.codex/skills/
```

Packaged `.skill` archives are available in `packages/`. Each skill provides
Chinese instructions in `SKILL.md` and a full English counterpart in
`SKILL.en.md`; the Chinese entry automatically directs English requests to the
English workflow.

## License

MIT
