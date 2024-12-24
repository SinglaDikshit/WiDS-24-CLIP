CLIP model

Contrastive learning Image Pre-training
Images and text dataset connect them in non-generative way
DALLE -generative
model that can represent image and text really well
CLIP- image to text prediction
DALL-E- text to image prediction

Zero shot image net accuracy-
CLIP > bag of words > transformer lang model(efficiency)
not trained but restrict it possible outcomes/classes 

diagonal entries match in the image and we have apply SoftMax function vertically and horizontally 
large mini batches
image and text classifier can be made(zero training)
image encoder-resnet/Vit
efficiency is increased by prompt engg. and ensembling
Zero shot CLIP is competitive with a fully supervised baseline.
linear probing
Linear Probing is a collision resolution method in hashing where, if a key hashes to an already occupied index, the next available slot is searched sequentially. The probing follows the formula (h(k)+i)%N, where i increments until an empty slot is found. It is simple and cache-friendly but suffers from primary clustering, where consecutive occupied slots form, reducing efficiency as the table gets filled. It works best with low load factors (e.g., < 0.7) and is commonly used in open-addressing hash tables.

Pretrained models on ImageNet, such as ResNet, VGG, and AlexNet, are widely used as starting points for transfer learning.
As the dataset increases efficiency increases.
Robustness of data shift - as dataset becomes more difficult, imagenet results become worse but zero shot CLIp remains in that range only but fluctuates
