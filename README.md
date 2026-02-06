# Pars Charts

Helm charts for Pars DAO infrastructure.

## Charts

| Chart | Description |
|-------|-------------|
| governance | DAO governance contracts |
| treasury | Treasury management |
| voting | Voting system |

## Usage

```bash
helm repo add parsdao https://parsdao.github.io/charts/
helm repo update
helm install my-governance parsdao/governance
```

## Development

```bash
# Lint charts
ct lint --all

# Test charts
ct install --all
```

