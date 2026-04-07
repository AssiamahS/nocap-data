# nocap-data

Training data and validation results for the nocap rep counter.

## Structure

```
results/          # JSON results from rep counting
  {video}_{exercise}.json
```

## Video Storage

Videos are stored in Google Drive (too large for git): `push up data/` folder.

## Result Format

Each JSON file contains:
- `reps_counted` - what the algorithm detected
- `reps_actual` - ground truth (filled in by user)
- `rep_quality` - per-rep quality notes (clean, grinder, half, etc.)
- Pose detection metadata (timestamps, angles, detection rate)
