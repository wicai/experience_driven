Pipeline is python -> R

Python:
scrape_league -> get_user_ids -> get_match_histories -> pull_individual_games -> parse_raw_games

R:
make_big_table_stats.Rmd -> 
bootstrap_stats.Rmd, by_champ_stats.Rmd, randomization_inference.Rmd ->
make_plots_stats.Rmd
