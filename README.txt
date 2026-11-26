VU3INI Humanizer 1.0.0
By Sasanka Boruah (VU3INI) - hamvu3ini@gmail.com

Rewrites AI-sounding text and documents so they read like a person wrote them,
without changing what they say. Built on blader/humanizer (MIT licence), whose
26 patterns come from Wikipedia's "Signs of AI writing".

START
  Start menu or desktop: "VU3INI Humanizer". The program runs a small server on
  this computer and opens its window in your web browser at
  http://127.0.0.1:47115  (no internet needed for the built-in Rules engine).

ENGINES
  Rules ........ built in, offline, instant, no model
  Ollama ....... local AI on CPU, NVIDIA GPU or both (install Ollama once and
                 download a model from Settings > AI engine)
  OpenAI-compatible (LM Studio, llama.cpp server, Jan, vLLM, OpenAI)
  Anthropic Claude, Google Gemini (cloud, API key needed)

FILES
  .docx .docm .odt .md .txt .html - formatting is kept, only paragraph wording
  changes. Results are saved with a time stamp in Documents\VU3INI Humanizer.

DATA
  Program:   %LOCALAPPDATA%\Programs\VU3INI Humanizer
  Settings:  %APPDATA%\VU3INI Humanizer  (settings.json, history.json, log)

Full help: click Help inside the program, or press F1.
