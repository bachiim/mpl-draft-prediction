# To Do List

## Exploratory Data Analysis (EDA)
### ✅ Done:
- Top 10 Most Banned Heroes
- Top 10 Most Picked Heroes
- Total Games by Patch Version
- Top 10 Heroes by Banrate per Patch Version
- Top 10 Heroes by Pickrate per Patch Version
- Hero Ban/Pick per Steps

### ❌ Not Yet:

## Modeling
### ✅ Done:
- Preprocessing
- Random Forest -> score=0.5
- ANN -> score=0.5 | top5=0.81

### ❌ Not Yet:

### 📝 Notes:
- input model -> (patch version, team 1, team 2, [step 1, ..., step n] -> encode/one-hot encoding, banrate(one-hot encoding), pickrate(one-hot encoding))
- output model -> step n+1
- baseline model -> Random Forest
