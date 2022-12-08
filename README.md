# One shot conversion with a VAE

---
layout: default
---
This is the demo page for the paper [One-shot Voice Conversion by Separating Speaker and Content Representations with Instance Normalization](https://arxiv.org/abs/1904.05742)
 
Voice conversion is the task of altering the voice of a speaker without changing the linguistic content. 
The typical set-up of this problem defines a source speaker who provides a sample of speech, and a target speaker 
whose voice will be used to reconstruct the source speaker's speech. A one-shot approach is when the model is only
supplied with one example of the source speaker, and one example of the target speaker. Neither of the source, nor 
target speakers need to be represented inside the training dataset. One-shot voice conversion
represents one of the most useful and challenging tasks in the VC domain: it requires minimal examples from a target 
speaker and also poses the least constraints on this example's content.


- - -
### *Male to male(p237->p292)*
- - -
#### *Source*
<audio src="res/demo/p237_p292_M_M/p237_018_p292_155_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p237_p292_M_M/p237_018_p292_155_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p237_p292_M_M/p237_018_p292_155_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p237_p292_M_M/p237_087_p292_162_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p237_p292_M_M/p237_087_p292_162_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p237_p292_M_M/p237_087_p292_162_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p237_p292_M_M/p237_171_p292_407_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p237_p292_M_M/p237_171_p292_407_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p237_p292_M_M/p237_171_p292_407_con.wav" controls preload></audio>
- - -
### *Female to male(p262->p256)*
- - -
#### *Source*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p262_p256_F_M/p262_027_p256_150_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p262_p256_F_M/p262_056_p256_116_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p262_p256_F_M/p262_056_p256_116_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p262_p256_F_M/p262_056_p256_116_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p262_p256_F_M/p262_083_p256_101_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p262_p256_F_M/p262_083_p256_101_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p262_p256_F_M/p262_083_p256_101_con.wav" controls preload></audio>
- - -
### *Female to female(p276->p294)*
- - -
#### *Source*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p276_p294_F_F/p276_064_p294_069_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p276_p294_F_F/p276_162_p294_250_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p276_p294_F_F/p276_162_p294_250_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p276_p294_F_F/p276_162_p294_250_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p276_p294_F_F/p276_225_p294_114_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p276_p294_F_F/p276_225_p294_114_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p276_p294_F_F/p276_225_p294_114_con.wav" controls preload></audio>
- - -
- - -
### *Male to female(p278->p310)*
- - -
#### *Source*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p278_p310_M_F/p278_047_p310_324_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p278_p310_M_F/p278_053_p310_141_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p278_p310_M_F/p278_053_p310_141_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p278_p310_M_F/p278_053_p310_141_con.wav" controls preload></audio>
- - -
#### *Source*
<audio src="res/demo/p278_p310_M_F/p278_101_p310_343_src.wav" controls preload></audio>
#### *Target*
<audio src="res/demo/p278_p310_M_F/p278_101_p310_343_tar.wav" controls preload></audio>
#### *Converted*
<audio src="res/demo/p278_p310_M_F/p278_101_p310_343_con.wav" controls preload></audio>
- - -
