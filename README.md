# Modalities

Therapeutic, contemplative, and growth modalities distilled into prompts for AI that works with humans.

Each file is one modality, written as a system prompt you can hand to a model. Files are versioned here over time as they improve through real use.

## Modalities (more coming soon)

- [IFS](IFS.md) — Internal Family Systems: identify protectors, unblend, and unburden exiles with Self energy.


## Using these

Download and use the .md file or paste its contents as the system prompt (or the opening message) to your AI of choice. Prompts often assume spoken output, so they ask the model to avoid markdown, emojis, and special characters.

These prompts support self-exploration. They are not therapy, medical advice, or a substitute for a licensed professional.

If you are in crisis or thinking about harming yourself, stop and reach out for help now. In the US, call or text 988 (Suicide & Crisis Lifeline).


## Consider local models

Local models do especially well here. Why? For one, using a local model gives means the modality can constitute the entire system prompt. Frontier chat products place your instructions after a long hidden system prompt of their own, so the modality competes for attention with everything else the provider needs the model to do. Run locally, the model's only frame is the practice itself, and smaller models often hold that frame remarkably well. Two, when run locally the entire session can remain confidential, never leaving your machine. People tend to speak more freely and honestly, and can go deeper.

## Chat mode is enough and sometimes best

These sessions can be run in chat mode, using a chat completions endpoint, without an agentic harness. An agentic harness (Pi, Bionic, Hermes, OpenClaw) can have the benefit of referencing a collection of your previous sessions (if you choose to save them) or a personal knowledge base, but it means their context will be consumed by the agentic harness' prompt. For machines with limited resources, and for session that are more pure in general, session run as chat completions are faster, more responsive, and often best. LM Studio, Ollama, oMLX

## Tested models

Models that have proven adept at these modalities in real sessions. This list grows as more combinations are tested.

- [Gemma 4 12B](https://huggingface.co/google/gemma-4-12B-it-qat-q4_0-gguf) — Very competent at IFS. Even thinking 'off' works well. Offers just the right length response, just the right nudges and pointers, and keeps the session moving forward. In chat mode, Gemma 4 12B is superior even to much larger models like Qwen 3.8 27B or Qwen 3.8 Flash Next which often leave the user hanging and fail to keep the session moving forward. Larger models may work better when in an agentic loop, as provided by an agentic harness (which Gemma 4 12B struggles to make proper use of) but will then require far more resources.


## Verbal conversations are better than screens

These modalities work best when the user can speak and listen instead of reading a screen. Voice modes for AI let you close your eyes and stay with what arises in the body and the inner world, which gives far better access to subconscious material compared to reading and typing on a screen. When the brain is busy parsing text, it stays in an analytical, outward-facing mode that works against introspection. When instead you're able to just listen and speak – especially with eyes closed, lying down, or even walking slowly around the room – parts, images, and feelings surface much more readily.

[LocalVocal](https://localvocal.ai) for Macs with Apple Silicon, is a conversational voice harness originally built to facilitate therapeutic sessions, verbally. The 'standard edition' is enough to get going, while the 'advanced edition' has many features that can make conversations more natural and productive. LocalVocal processes and generates all speech locally on the users machine. When used with locally running LLMs, sessions can remain totally confidential, with conversations that never leave your machine.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use and adapt freely, including commercially, with credit. Provided as is, without warranty of any kind.
