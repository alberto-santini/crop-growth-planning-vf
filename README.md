# The Crop Growth Planning Problem in Vertical Farming

This repository contains the instances used in the paper "The Crop Growth Planning Problem in Vertical Farming", by [Alberto Santini](https://santini.in/), [Michael Schneider](https://www.dpo.rwth-aachen.de/cms/DPO/Der-Lehrstuhl/Team/Lehrstuhlleitung/~nwkh/Michael-Schneider/), [Enrico Bartolini](https://www.dpo.rwth-aachen.de/cms/DPO/Der-Lehrstuhl/Team/Post-Doktorand/~nwla/Enrico-Bartolini/lidx/1/) and [Vinicius Greco de Lemos](https://www.linkedin.com/in/viniciusgreco/).

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Indoor_Hydroponics_of_Morus%2C_Japan_%2838459770052%29.jpg/640px-Indoor_Hydroponics_of_Morus%2C_Japan_%2838459770052%29.jpg"><br>
    Growing mulberries in a hydroponic system. Photograph by Satoshi Kinokuni, distributed under a CC-BY-2.0 license.
</p>

## Instance naming

Instances are named according to the following pattern:

```
<n_shelves>-<n_crops>-<crops>-<time_horizon>-<demand_mult>-<id>-<model_type>.dat
```

Where:

* `n_shelves` is the number of shelves in the cabinet.
* `n_crops` is the number of crops considered.
* `crops` are the actual crops in the instance (crops are named from A to F).
* `time_horizon` is the length of the planning horizon, in days.
* `demand_mult` is a demand multiplier.
* `id` is a number uniquely identifying the instance.
* For each instance, we provide three data files, with different values of `model_type`. This is because we propose multiple formulations for this problem. We refer to the paper for further details.

## Instance format

Instances use the Cplex Ilog `.dat` format and can be directly included in Ilog and work with any `.mod` file provided by the user.

## License

The instances are distributed under the GPLv3 license.
Find more details in the `LICENSE` file.
