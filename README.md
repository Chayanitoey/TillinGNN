# TillinGNN
Testing TillingGNN

Error message

C:\Users\matt->py C:\Users\matt-\Downloads\TilinGNN-master\TilinGNN-master\network_train.py
<class 'torch_geometric.data.dataset.Dataset'>
=================== Program Start ====================
Output directory: C:\Users\matt-\Downloads\TilinGNN-master\TilinGNN-master\util\..\debug\2023-02-15_22-28-19_training_100
config file created at C:\Users\matt-\Downloads\TilinGNN-master\TilinGNN-master\util\..\debug\2023-02-15_22-28-19_training_100\config.py
num_of_nodes : 200
num_of_adj_edges : 894
num_of_collide_edges : 2273
Processing...
processing the data...
Done!
Traceback (most recent call last):
  File "C:\Users\matt-\Downloads\TilinGNN-master\TilinGNN-master\network_train.py", line 41, in <module>
    save_model_per_epoch= config.save_model_per_epoch)
  File "C:\Users\matt-\Downloads\TilinGNN-master\TilinGNN-master\solver\ml_solver\trainer.py", line 72, in train
    loader_train = DataLoader(dataset_train, batch_size=batch_size, shuffle=True)
  File "C:\Users\matt-\AppData\Local\Programs\Python\Python37\lib\site-packages\torch_geometric\loader\dataloader.py", line 83, in __init__
    **kwargs,
  File "C:\Users\matt-\AppData\Local\Programs\Python\Python37\lib\site-packages\torch\utils\data\dataloader.py", line 344, in __init__
    sampler = RandomSampler(dataset, generator=generator)  # type: ignore[arg-type]
  File "C:\Users\matt-\AppData\Local\Programs\Python\Python37\lib\site-packages\torch\utils\data\sampler.py", line 108, in __init__
    "value, but got num_samples={}".format(self.num_samples))
ValueError: num_samples should be a positive integer value, but got num_samples=0
