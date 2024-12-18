## Dependencies

```bash
pip install ffmpeg-python
```

## Usage

Run `python lec{n}.py` to produce a lecture video. The DSL defined in `lib.py`
is pretty simple; look at any of the processing scripts for any lecture video,
and it should be clear how to make new ones.

To type-check the code, run:

```bash
mypy .
```

## License

Copyright (c) 2024 Ashay Athalye, Anish Athalye, Jose Javier, and Jon Gjengset. Released under
the MIT License. See [LICENSE.md](LICENSE.md) for details.
