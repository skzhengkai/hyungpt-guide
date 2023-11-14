# `/music-generator`

Generates AI-generated music from a text prompt. 

## Usage

```
/music-generator <subcommand> <options>  
```

## Subcommands  

### `simple`

Generates music using a simple model.

```  
/music-generator simple --prompt:"a happy orchestral tune"
```

Options:

- `--prompt` - Text describing the music to generate. Required.

- `--denoising` - How much to transform input spectrogram. Default 0.75.  

- `--num_inference_steps` - Diffusion model steps. Default 50.

### `premium`

Generates music using a high quality model. Requires premium. 

```
/music-generator premium --prompt "80s synthwave" --duration 10
```

Options:

- `--prompt` - Text describing the music. Required.

- `--duration` - Length of audio in seconds. Default 8.

- `--seed` - Random seed.

## Access Requirements

- `simple` requires voting on top.gg or premium status.

- `premium` requires premium subscription.

## Examples  

Simple model:

```  
/music-generator simple --prompt "cheerful piano melody in a major key"
```

Premium model:

```
/music-generator premium --prompt "upbeat jazz with saxophone" --duration 15
```

The music generator allows you to turn text into audio!