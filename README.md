# Segmenter Variational Autoencoder

This VAE has the ability to   generate from within the distribution of satellites images, a generative image  representative of the entire dataset with  colored distinct patterns mapped into a RGB Space.

# Hyperparameters
| Hyperparameters        | Values        |
| -------------          |:-------------:|   
| Epochs                 | 2 | $
| batch size             | 32           |  
| learning rate          | 1e-4         |
| dropout                | 0.5           |  
| mse_weight             | 1             |  
| KLDiv_weight           | 1e-3            |
| LSTM Layers            | 2             |   
| Hidden activation      | SeLU           |
| Latent activation      | Sigmoid           |

# The dataset
Data represents satellites images of cities with multiples objects.
<img width="782" alt="Capture d’écran 2020-12-03 à 2 22 20 AM" src="https://user-images.githubusercontent.com/55285736/100951204-61b50680-350e-11eb-917e-f2a6a894e5db.png">



# Compressed representation of the dataset
The resulted image shows interesting result, where  objects are segmented with a specific color which make us able to distinguish an item from another. 
<img width="500" alt="Capture d’écran 2020-12-03 à 1 58 51 AM" src="https://user-images.githubusercontent.com/55285736/100949929-95426180-350b-11eb-9491-ee8f303e49f8.png">
