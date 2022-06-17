| Column                             | Useful? | Note                                                                                                      | Insight from Graph                 |
| ---------------------------------- | ------- | --------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| 'production_company'               | No      | all currently are Netflix/Netflix Originals                                                               |                                    |
| 'show_id'                          | No      |                                                                                                           |                                    |
| 'type'                             | No      | All are 'Movie'                                                                                           |                                    |
| 'title'                            |         |                                                                                                           |                                    |
| 'movie_title'                      | No      | same as above                                                                                             |                                    |
| 'director'                         |         | directors frequently used/not-used? check against RT                                                      |                                    |
| 'cast'                             |         | strings of actors (any that NF lean on/underuse?)                                                         |                                    |
| 'country'                          |         | of production                                                                                             |                                    |
| 'date_added'                       |         |                                                                                                           |                                    |
| 'release_year_x'                   |         |                                                                                                           |                                    |
| 'release_year_y'                   | no      | same as above (as these are matched on slug)                                                              |                                    |
| 'rating'                           |         | group by guidance rating to see where they already skew                                                   | Most are TV-MA                     |
| 'content_rating'                   |         |                                                                                                           | Most are not rated                 |
| 'duration'                         |         | Has a string at the end so not helpful                                                                    |                                    |
| 'runtime'                          |         |                                                                                                           |                                    |
| 'listed_in'                        |         | NF categories                                                                                             |                                    |
| 'description'                      | no      |                                                                                                           |                                    |
| 'movie_info'                       | no      | as description                                                                                            |                                    |
| 'title_and_release_year'           | no      | slug                                                                                                      |                                    |
| 'rotten_tomatoes_link'no           |         |                                                                                                           |                                    |
| 'critics_consensus'                | no      | general text                                                                                              |                                    |
| 'genres'                           |         | Need to split genres into individual genres                                                               |                                    |
| 'directors'                        |         | Need to split directors into individual directors                                                         |                                    |
| 'authors'                          |         | Need to split authors into individual authors                                                             |                                    |
| 'actors'                           |         | Need to split actors into individual actors                                                               |                                    |
| 'original_release_date'            |         |                                                                                                           |                                    |
| 'streaming_release_date'           |         |                                                                                                           |                                    |
| 'tomatometer_status'               | Maybe   | String, might be useful for broad stroke when tomatometer rating not used                                 |                                    |
| 'tomatometer_rating'               |         |                                                                                                           |                                    |
| 'tomatometer_count'                |         |                                                                                                           | Most Netflix OC is not rated on RT |
| 'audience_status'                  | Maybe   | String, might be useful for broad stroke when audience rating not used                                    |                                    |
| 'audience_rating'                  |         |                                                                                                           |                                    |
| 'audience_count'                   |         | Is this a count of people who have voted on RT rather than a viewing figure? Still need to have viewed it | Most Netflix OC is not rated on RT |
| 'tomatometer_top_critics_count'    |         |                                                                                                           | Most Netflix OC is not rated on RT |
| 'tomatometer_fresh_critics_count'  |         |                                                                                                           | Most Netflix OC is not rated on RT |
| 'tomatometer_rotten_critics_count' |         |                                                                                                           | Most Netflix OC is not rated on RT |
| 'matched_to_rt'                    | No      | All are already matched                                                                                   |                                    |
