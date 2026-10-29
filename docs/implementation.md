# Medical Image Classification Research Assistant — implementation

Data input → validation → train/test split → baseline models → error analysis and metrics → model serialization → FastAPI prediction → unit tests.

Run `python engine.py train`; then `python -m unittest discover -s tests -v`. Serve locally using `uvicorn api:app --reload`.

**Limitation:** Images are synthetic. Not a clinical diagnosis tool.
