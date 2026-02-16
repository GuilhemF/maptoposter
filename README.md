# City Map Poster Generator (Fork)

> ⚠️ **Note:** This is a modified version of the [original project by originalankur](https://github.com/originalankur/maptoposter).
>
> **What's new in this fork?**
> I added the `--show-point` feature. This optional argument places a marker at the exact center coordinates of the map, allowing you to pinpoint a specific location on the poster.

Generate beautiful, minimalist map posters for any city in the world.

<img src="posters/singapore_neon_cyberpunk_20260118_153328.png" width="250">
<img src="posters/dubai_midnight_blue_20260118_140807.png" width="250">

## Installation

### With uv (Recommended)

Make sure [uv](https://docs.astral.sh/uv/) is installed. Running the script by prepending `uv run` automatically creates and manages a virtual environment.

```bash
# First run will automatically install dependencies
uv run ./create_map_poster.py --city "Paris" --country "France"

# Or sync dependencies explicitly first (using locked versions)
uv sync --locked
uv run ./create_map_poster.py --city "Paris" --country "France"