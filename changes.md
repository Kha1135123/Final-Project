# Changes since last presentation
- Fix interactions matrix shape ([n_items,n_users] to [n_users,n_item]) which was causing the LightFM model to work not properly.
- Fix informations in the presentation HackMD slide (Re-state TEFPA, add new model's AUC score)
- Added user features based on Food types. Each weight over features is calculated by the sum of a user's ratings of a specific food type divide by total ratings that user gived for all items
- Slightly modify recommend functions to create initial user embedding for new users which later get updated when ratings is available. Initial embedding is only assumption values though.
- Initial embedding created by ticking checkboxes in Demo Gradio UI. For more details please view this [recommend functions code](https://github.com/Kha1135123/FoodRecommenderSystem_FinalProject/blob/main/create_recsys.py), line 133-161.
