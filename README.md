# cougar-or-not

NOTE: Most of the work in this repo is by [@simonw](https://github.com/simonw). I'm stealing it to bootstrap some exercises in my FastAI course. 20200104 @matsaleh13

`bears.py` is a very tiny [Starlette](https://www.starlette.io/) API server which simply accepts file image uploads and runs them against the pre-calculated model.

It also accepts a URL to an image, e.g. https://localhost/classify-url?url=https://path-to-bear-image.jpg

The `Dockerfile` means the entire thing can be deployed to [Zeit Now](https://zeit.co/now) or any other container hosting service.
