<p align="center">
  <img src="https://raw.githubusercontent.com/madhavcodez/madhavcodez/main/assets/hero.svg" alt="Madhav Chauhan" width="100%"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/madhav-s-c">linkedin</a> &middot;
  <a href="mailto:madhavcbusiness@gmail.com">email</a> &middot;
  <a href="https://madhavchauhan.tech">portfolio</a>
</p>

---

### now

i like building

Recent work:
- **[microscope](https://github.com/madhavcodez/microscope)** &mdash; Reproducible mechanistic-interpretability toolkit: sparse autoencoders, transcoders, auto-interp, and feature circuits on Gemma-2-2B, with adversarial controls and honest-evaluation-first scoring.
- **[Agentary](https://github.com/madhavcodez/agentary)** &mdash; Autonomous multi-agent research platform.
- **[cortex-score](https://github.com/madhavcodez/cortex-score)** &mdash; Score any video for predicted cortical engagement across 5 brain networks (built on Meta FAIR&rsquo;s TRIBE v2).

### previously

- **[UT Disaster](https://github.com/UTDisaster)** &mdash; Professor-led disaster damage assessment platform: VLM pipeline on pre/post Hurricane Florence satellite imagery, React map UI, FastAPI + PostGIS backend with natural-language spatial Q&amp;A.
- **SentinelEdge** &mdash; Smart security cameras for small businesses: runs threat detection on a small on-site computer (NVIDIA Jetson Nano) and pings the owner&rsquo;s phone in under 2 seconds, with no cloud round-trip. Funded pilot with a local gas-station owner.
- **[rajputra.org](https://rajputra.org)** &mdash; Community engagement portal serving 10K+ monthly visitors.
- **Inventory Tracking System** &mdash; Nonprofit warehouse platform for Hope Restored Missions: Nuxt 3 + Vue 3 + Prisma + PostgreSQL replacing spreadsheet-based tracking, with C-based QR / barcode scanning compiled to WebAssembly. Led a five-engineer team.
- **Access Control Manager** &mdash; Embedded access controller for The Lab.ms makerspace: ESP32 + 13.56 MHz RFID + fingerprint authentication on a custom PCB, with FreeRTOS firmware keeping audit trails reliable through network outages.

---

### open source

Curious builder interested in quantum computing, robotics, embedded systems, computer vision, and edge ML. AI / ML is where I&rsquo;ve spent the most time so far.

**Merged contributions:**
- **[roboflow/supervision](https://github.com/roboflow/supervision)** &mdash; Open-source computer vision toolkit (39k+ stars). [PRs](https://github.com/roboflow/supervision/pulls?q=is%3Apr+author%3Amadhavcodez)
  - [#2281](https://github.com/roboflow/supervision/pull/2281) windowed GeoTIFF reads in `InferenceSlicer` &middot; [#2284](https://github.com/roboflow/supervision/pull/2284) CreateML dataset format &middot; [#2299](https://github.com/roboflow/supervision/pull/2299) LabelMe dataset format
  - [#2276](https://github.com/roboflow/supervision/pull/2276) 1-indexed COCO `category_id` export &middot; [#2267](https://github.com/roboflow/supervision/pull/2267) chainable COCO ids across splits &middot; [#2266](https://github.com/roboflow/supervision/pull/2266) docs CLI-flag fix
- **[geopandas/geopandas](https://github.com/geopandas/geopandas)** &mdash; Geospatial data in Python (4.7k+ stars). [#3784](https://github.com/geopandas/geopandas/pull/3784) honor `legend_kwds["labels"]` for categorical and boolean columns in `explore()`
- **[roboflow/inference](https://github.com/roboflow/inference)** &mdash; Computer-vision inference server &amp; Workflows engine (2.3k+ stars). [#2388](https://github.com/roboflow/inference/pull/2388) correct `values_difference` aggregation in the Data Aggregator block
- **[python-pendulum/pendulum](https://github.com/python-pendulum/pendulum)** &mdash; Python datetimes made easy (6.6k+ stars). [#974](https://github.com/python-pendulum/pendulum/pull/974) allow `None` for `exc_tb` in `Traveller.__exit__` type annotations

**Approved &amp; merging:**
- **[redis/redis-py](https://github.com/redis/redis-py)** &mdash; Python client for Redis (13k+ stars). [#4088](https://github.com/redis/redis-py/pull/4088) PyPI Trusted Publishing (OIDC) for releases &mdash; maintainer confirmed it will be merged once their release steps land.

**In review:**
- **[voxel51/fiftyone](https://github.com/voxel51/fiftyone)** &mdash; Dataset and visual-AI toolkit for computer vision (10k+ stars). [#7830](https://github.com/voxel51/fiftyone/pull/7830) validate longitude / latitude ranges on geo fields &middot; [#7831](https://github.com/voxel51/fiftyone/pull/7831) load extra CityPersons attributes on Cityscapes person detections
- **[shapely/shapely](https://github.com/shapely/shapely)** &mdash; Manipulation and analysis of geometric objects (4.4k+ stars). [#2459](https://github.com/shapely/shapely/pull/2459) document the `.xy` limitation on polygons and multi-part geometries
- **[rasterio/rasterio](https://github.com/rasterio/rasterio)** &mdash; Geospatial raster I/O for Python (2.5k+ stars). [#3578](https://github.com/rasterio/rasterio/pull/3578) accept 3-vertex polygons (triangles) in `is_valid_geom` and `rasterize`
- **[geopandas/geopandas](https://github.com/geopandas/geopandas)** &mdash; [#3789](https://github.com/geopandas/geopandas/pull/3789) keep `crs` when `from_features` gets an empty feature list
- **[geopandas/contextily](https://github.com/geopandas/contextily)** &mdash; Context basemap tiles for matplotlib / geopandas (580+ stars). [#282](https://github.com/geopandas/contextily/pull/282) fix a missing return in `_retryer` that propagated `None` tiles
- **[pyproj4/pyproj](https://github.com/pyproj4/pyproj)** &mdash; Python interface to PROJ cartographic projections (1.2k+ stars). [#1604](https://github.com/pyproj4/pyproj/pull/1604) document late-binding behavior of `Transformer` serialization
- **[torchgeo/torchgeo](https://github.com/torchgeo/torchgeo)** &mdash; Geospatial deep learning for PyTorch. [#3770](https://github.com/torchgeo/torchgeo/pull/3770) convert `WesternUSALiveFuelMoisture` to the time-series sample format
- **[unionai-oss/pandera](https://github.com/unionai-oss/pandera)** &mdash; Statistical data validation for dataframes (4.3k+ stars). [#2395](https://github.com/unionai-oss/pandera/pull/2395) raise a clear `TypeError` for non-DataFrame `validate` arguments
- **[arogozhnikov/einops](https://github.com/arogozhnikov/einops)** &mdash; Flexible tensor operations for readable code (9.5k+ stars). [#436](https://github.com/arogozhnikov/einops/pull/436) document the broadcast / expand semantics of `einops.repeat`
- **[redis/redis-py](https://github.com/redis/redis-py)** &mdash; [#4124](https://github.com/redis/redis-py/pull/4124) cache default response callbacks instead of rebuilding them on every client init
- **[stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)** &mdash; Stanford&rsquo;s framework for programming language models (34k+ stars). [#9832](https://github.com/stanfordnlp/dspy/pull/9832) preserve Python literals in `ChatAdapter` dict parsing
- **[niivue/niivue](https://github.com/niivue/niivue)** &mdash; Web-based neuroimaging visualization. [#1612](https://github.com/niivue/niivue/pull/1612) fix reversed translucent / transparent volume rendering
- **[swar/nba_api](https://github.com/swar/nba_api)** &mdash; Python client for NBA.com. [#676](https://github.com/swar/nba_api/pull/676) 2026 WNBA expansion teams &middot; [#677](https://github.com/swar/nba_api/pull/677) team conference / division static data

Looking for more meaningful projects to contribute to. If you maintain something in any of those areas and want a hand, point me at an issue: [madhavcbusiness@gmail.com](mailto:madhavcbusiness@gmail.com).

Also happy to take issues / PRs on [cortex-score](https://github.com/madhavcodez/cortex-score) &mdash; the only public surface of my brain-encoding work.

---

<p align="center">
  <sub>shipping from dallas &middot; university of texas (dallas) alum, class of &rsquo;26 &middot; open to swe / ml roles</sub>
</p>
