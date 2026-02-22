# Internet Provider Concentration Risk AI

Score concentration risk from provider dependency patterns.

## Priority Metadata

- ID: 167
- Domain: internet
- TTE (days): 4
- Exposure score: 7/10
- Wave: 1
- Priority score: 6.60

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
