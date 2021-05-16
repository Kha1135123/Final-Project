# Final-Project

- Recomender System
- Using LightFM - Hybrid Model


- If you want to reset data, write this code down:

```

interactions = csr_matrix((df_train_rating["rating"], (row, col)), \
                           shape=(item_c.categories.size, user_c.categories.size))
user_dict = create_user_dict(df_train_rating,'user_id','u')
name_dict = {}
