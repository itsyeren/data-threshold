# Threshold Adjustments

## Download the dataset

The dataset is available [here](https://d32aokrjazspmn.cloudfront.net/materials/ML_New_player.csv). Let's download it with the following commands and save it to the `data` folder in the `03-Threshold-Adjustments` directory:

```bash
curl https://d32aokrjazspmn.cloudfront.net/materials/ML_New_player.csv > data/player_performances.csv
```

## Dataset

- Each observation represents a player
- Each column is a feature of performance
- The target `target_5y` defines whether the player has less than 5 years [0] or 5 years or more [1] of professional career experience.

## Exercise

🎯 In this exercise, we are a Data Scientist for a professional basketball team.

The coach wants us to help him with the recruitment process. We need to identify players who will remain professional for a minimum of 5 years. However, we don't want to take any risks and warn us that we want a 90% guarantee that any player we send them will actually remain professional for 5 years.
