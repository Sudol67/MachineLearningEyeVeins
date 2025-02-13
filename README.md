# Wykrywanie naczyń dna siatkówki oka

Kod implementujący uczenie maszynowe w celu segmentacji zdjęć dna oka i wyodrębnieniu naczyń krwionośnych. 
Dane zostały podzielone na:
* Kolorowe zdjęcie oka z widocznymi naczyniami krwionośnymi
* Zdjęcia z ręcznie zrobioną adnotacją o lokalizacji naczyń krwionośnych

Każde zdjęcie z ręczną adnotacją odpowiada jednemu zdjęciu oryginalnemu. Wczytując jako dane uczące te zestawy zdjęć, model uczy się segmentować żyły. 

Kod wymaga dopracowania parametrów w celu większej skuteczności. Dostępne są także inne zestawy zdjęć w celu dalszego treningu lub testowania modelu.

# Detection of retinal fundus vessels

Code implementing machine learning to segment fundus images and extract blood vessels. 
The data was segmented into:
* Color photo of the eye with blood vessels visible.
* Photographs with hand-made annotation of the location of blood vessels.

Each manually annotated photo corresponds to one original photo. By loading these sets of photos as teaching data, the model learns to segment the veins. 

The code needs to have its parameters refined to be more effective. Other sets of images are also available for further training or testing of the model.
