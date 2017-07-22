# dlnd-project5 - Face Generation
In this project, we'll use generative adversarial networks to generate new images of faces.

## Environment: Tensorflow 1.0
floyd run --env tensorflow-1.0 --mode jupyter --gpu --data R5KrjnANiKVhLWAkpXhNBe:input "ls -la /input"

## Data
We'll be using two datasets in this project:
- MNIST
- CelebA
- URL: https://www.floydhub.com/viewer/data/R5KrjnANiKVhLWAkpXhNBe/DVeJfRKoK45Kb84Q9LkKJj/


## Hyperparameters Used:
MNIST
- batch_size = 64
- z_dim = 200
- learning_rate = 0.001
- beta1 = 0.01

Result after training: Epoch 2/2... Discriminator Loss: 1.4570... Generator Loss: 0.4947

CelebA
- batch_size = 64
- z_dim = 200
- learning_rate = 0.001
- beta1 = 0.5

Result after training: Epoch 1/1... Discriminator Loss: 1.3002... Generator Loss: 0.7809