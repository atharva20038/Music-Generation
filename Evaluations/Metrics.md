| Model     | Sample Rate↑ | Len.↑    | Input (Text ✓)            | Music (Diverse↑)            | Example         | Infer. Time↓         | Data  |
|-----------|---------------|----------|---------------------------|-----------------------------|------------------|----------------------|-------|
| WaveNet   | 16kHz@1       | Secs     | None                      | Piano or speech             | Piano            | = Audio len.☆        | 260   |
| Jukebox   | 44.1kHz@1     | Mins☆    | Lyrics, author, etc.      | Song with the lyrics        | Song             | Hours                | 70K   |
| RAVE      | 48kHz@2       | Secs☆    | Latent                    | Single-genre Music          | Strings          | = Audio len.☆        | 100   |
| AudioLM   | 16kHz@1       | Secs☆    | Beginning of the music    | Piano or speech             | Piano            | Mins                 | 40K   |
| Musika    | 22.5kHz@2     | Secs     | Context vector            | Single-genre Music          | Piano            | = Audio len.☆        | 1K    |
| Riffusion | 44.1kHz@1     | 5s       | Text (genre, author, etc.)| Music of any genre          | Jazzy clarinet   | Mins                 | –     |
| AudioGen  | 16kHz@1       | Secs☆    | Text (a phrase/sentence)  | Daily sounds                | Dog barks        | Hours                | 4K    |
| Mousai    | 48kHz@2       | Mins☆    | Text (genre, author, etc.)| Music of any genre          | African drums    | = Audio len.☆        | 2.5K  |
