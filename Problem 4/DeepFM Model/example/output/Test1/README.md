
Submissions are saved here.

dfm_params = {
"use_fm": True,
"use_deep": True,
"embedding_size": 8,
"dropout_fm": [1.0, 1.0],
"deep_layers": [4, 4],
"dropout_deep": [0.5, 0.5, 0.5],
"deep_layers_activation": tf.nn.relu,
"epoch": 30,
"batch_size": 1024,
"learning_rate": 0.001,
"optimizer_type": "adam",
"batch_norm": 1,
"batch_norm_decay": 0.995,
"l2_reg": 0.01,
"verbose": True,
"eval_metric": gini_norm,
"random_seed": config.RANDOM_SEED
}
