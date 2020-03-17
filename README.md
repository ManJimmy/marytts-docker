
## Usage
```
docker build -t tts .
docker run -p 59125:59125 tts
```

Visit http://localhost:59125/process?INPUT_TYPE=TEXT&AUDIO=WAVE_FILE&OUTPUT_TYPE=AUDIO&LOCALE=en_US&INPUT_TEXT=%22The%20rain%20in%20spain%20falls%20mainly%20in%20the%20plane%22