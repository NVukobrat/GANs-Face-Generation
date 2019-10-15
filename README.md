# Summary

## GANs overview
Generative Adversarial Networks (GANs) belongs to the generative models. That means they are able to generate artificial content base on the arbitrary input.

Generally, GANs most of the time refers to the training method, rather on the generative model. Reason for this is that GANs don't train a single network, but instead two networks simultaneously.

The first network is usually called Generator, while the second Discriminator. Purpose of the Generator model is to images that look real. During training, the Generator progressively becomes better at creating images that look real. Purpose of the Discriminator model is to learn to tell real images apart from fakes. During training, the Discriminator progressively becomes better at telling fake images from real ones. The process reaches equilibrium when the Discriminator can no longer distinguish real images from fakes.

## Environment
- **OS:** Ubuntu 19.04
- **Processor:** Intel Core i7-4770 CPU @ 3.40GHz × 8
- **Graphics:** GeForce GTX 1080 Ti/PCIe/SSE2
- **Memory:** Kingston HyperX Fury Red 16 GB (2 x 8 GB)
- **Language:** Python 3.5.2 with TensorFlow 2.0.0b1 (Dockerized version)

# Dataset
The dataset used for generating face images comes in two forms. First is [Thumbnails 128x128](https://drive.google.com/drive/folders/1tg-Ur7d4vk1T8Bn0pPpUSQPxlPGBlGfv). Second is [Thumbnails 1024x1024](https://drive.google.com/drive/folders/1tZUcXDBeOibC6jcMCtgRRz67pzrAHeHL). Both represent images containing only human faces. Shape of the images varies in two forms: 128x128x3 and 1024x1024x3, where they represent Width, Height and Channels respectively.

# Results
Results are grouped in III groups by processing image size:
- 28x28x3
- 56x56x3
- 112x112x3

Where values represent Width, Height and Channels respectively. Regarding used models, Discriminator model stayed the same, while Generator model is changed in order to generate different sizes of faces. Changes are related by adding additional layers to up-sample images further.

For each sample size type training last about **1d 3h 27m**.

## Samples
### 28x28x3 (orange)
<table>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00010_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00020_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00030_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00040_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00050_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00060_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00070_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00080_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00090_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00110_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00120_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00130_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00140_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00150_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00160_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00170_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00180_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00190_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00210_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00220_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00230_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00240_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00250_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00260_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00270_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00280_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00290_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00310_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00320_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00330_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00340_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00350_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00360_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00370_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00380_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00390_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00410_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00420_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00430_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00440_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00450_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00460_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00470_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00480_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00490_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00510_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00520_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00530_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00540_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00550_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00560_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00570_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00580_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00590_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00610_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00620_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00630_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00640_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00650_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00660_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00670_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00680_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00690_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00710_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00720_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00730_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00740_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00750_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00760_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00770_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00780_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00790_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00810_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00820_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00830_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00840_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00850_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00860_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00870_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00880_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00890_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_00900_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00910_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00920_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00930_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00940_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00950_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00960_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00970_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00980_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_00990_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01010_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01020_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01030_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01040_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01050_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01060_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01070_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01080_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01090_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01110_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01120_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01130_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01140_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01150_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01160_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01170_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01180_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01190_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01210_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01220_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01230_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01240_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01250_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01260_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01270_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01280_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01290_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01310_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01320_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01330_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01340_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01350_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01360_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01370_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01380_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01390_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01410_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01420_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01430_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01440_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01450_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01460_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01470_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01480_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01490_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01510_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01520_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01530_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01540_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01550_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01560_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01570_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01580_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01590_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01610_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01620_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01630_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01640_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01650_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01660_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01670_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01680_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01690_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01710_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01720_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01730_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01740_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01750_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01760_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01770_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01780_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01790_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01810_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01820_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01830_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01840_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01850_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01860_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01870_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01880_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01890_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_01900_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01910_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01920_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01930_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01940_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01950_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01960_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01970_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01980_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_01990_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_02000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_02900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_03000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_03900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_04000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_04900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_05000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_05900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_06000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_06900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_07000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_07900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_08000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_08900_00000.png" alt=""></td>
	</tr>
	<tr>
		<td><img src="assets/result_samples/28/image_at_epoch_09000_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09100_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09200_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09300_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09400_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09500_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09600_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09700_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09800_00000.png" alt=""></td>
		<td><img src="assets/result_samples/28/image_at_epoch_09900_00000.png" alt=""></td>
	</tr>
</table>


### 56x56x3 (blue)
### 112x112x3 (red)

## Legend
Following sizes are represent in next colors:
- 28x28x3 = orange
- 56x56x3 = blue
- 112x112x3 = red

## Discriminator Accuracy
<table>
    <tr>
        <td>Discriminator on real images</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Accuracy_Real Discriminator.png" alt=""></td>
    </tr>
    <tr>
        <td>Discriminator on fake images</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Accuracy_Fake Discriminator.png" alt=""></td>
    </tr>
    <tr>
        <td>Discriminator combined mean loss</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Accuracy_Combined Discriminator.png" alt=""></td>
    </tr>
</table>

## Loss
<table>
    <tr>
        <td>Generator Loss</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Loss_Generator.png" alt=""></td>
    </tr>
    <tr>
    	<td>Discriminator Loss</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Loss_Discriminator.png" alt=""></td>
    </tr>
</table>

### Histograms
<table>
    <tr>
        <td>Generator Histogram</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/histogram_generator_1.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/histogram_generator_2.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/histogram_generator_3.png" alt=""></td>
    </tr>
    <tr>
    	<td>Discriminator Histogram</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/histogram_discriminator_1.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/histogram_discriminator_2.png" alt=""></td>
    </tr>    
</table>

### Distribution
<table>
    <tr>
        <td>Generator Distribution</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/distribution_generator_1.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/distribution_generator_2.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/distribution_generator_3.png" alt=""></td>
    </tr>
    <tr>
    	<td>Discriminator Distribution</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/distribution_discriminator_1.png" alt=""></td>
    </tr>
    <tr>
        <td><img src="assets/training_results/distribution_discriminator_2.png" alt=""></td>
    </tr>
</table>

### Training Speed
<table>
    <tr>
    	<td>Train epoch</td>
    </tr>
    <tr>
        <td><img src="assets/training_results/Execution time_Train epoch.png" alt=""></td>
    </tr>
</table>