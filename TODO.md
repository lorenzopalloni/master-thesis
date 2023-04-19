# TODO List


- [intro] visual representation of video restoration task
- [appendix] include VMAF table results
- [appendix] include descriptions of metrics

slide 3: io mi concentrerei sulle metriche che usi nello specifico, così fa un po' effetto lista della spesa. In generale nella presentazione ha senso concentrarsi sul tuo contributo innovitativo e lasciare perdere le info di background tranne quelle strettamente necessarie.

s4: qui forse ogni modello meriterebbe una slide con figura a parte, in particolare le GAN se uno non le conosce può valere la pena spiegarle meglio.

s5: questa slide contiene tanto cose diverse, non mi è molto chiaro il messaggio che vuoi trasmettere. Forse meglio spezzarla in due slides, una dove descrivi le tecninche di quantization che usi nella tesi e un'altra le ottimizzazioni a livello di computazione (amesso che tu voglia includerle, forse nella presentazione meglio risaltare la parte scientifica e lasciare perdere i dettagli più ingegneristici).

s6: sugli esperimenti, prima ci vorrebbe una slide che illustri le domande sperimentali che ti poni, spiegando perchè ha senso chiedersi quelle domande. Poi fai vedere una risultato per ogni domanda che ti sei posto e poi fai una slide di summary dove riassumi i punti principali. Questa slide richia di mettere un po' tanta carne al fuoco tutta in una volta.

s7-8-9: se possibile io metterei i plot invece che le tabelle, sono più intuitivi da comprendere per un commissione che in 10 minuti deve capire quello che hai fatto. E' normale che ci siano tanti risultati uguali sulle righe? E' un po' strano, preparati una spiegazione per questa cosa a voce :)

s10-11-12: personalmente toglierei la slide con gli alberi, le immagini sono scure e non si capisce molto. Forse meglio tenere solo una slide tra gli edifici e le persone, o metterle tutte nella stessa slide, alla fine entrambe le slides dicono la stessa cosa.

s14: Thank you è meglio di thanks, più formale. Metti logo UNIFI alla fine.


## high priority

- explain better metrics
- put VMAF results
- generate qualitative results showing only plain implementation vs INT8 of SRUNet on trees

- write presentation slides
- write presentation script
- define presentation structure

20 mins (15 mins + 5 mins of Q&As) -> 6 slides

1. intro
    - context
    - goals
2. metrics
    - non-perceptual vs perceptual metrics
3. architectures
    - UNet
    - SRUNet
4. optimizations
    - training
    - inference
5. experiments
6. conclusions

- bibliography
- appendix

## medium priority

## low priority

### Comments

## DONEs
- DONE - .gitignore literature/ folder, plus Python and LaTex stuff
- DONE - set up abstract
- DONE - simple makefile
- DONE - understand bibliography
- DONE - sync between local and Onyx files
- DONE - overleaf setup
- DONE - init git repo for the thesis
- DONE - convert sh script for video preparation to Python
- DONE - poetry vs conda: understand which one would be the best to manage the venv for the project
- DONE - study fast-sr-unet repo identifying from which file(s) to start copying/adapting
- DONE - start packaging the ./code/ folder in another repo
- DONE - explain PSNR
- DONE - explain SSIM
- DONE - explain MS-SSIM
- DONE - explain LPIPS-Comp / LPIPS
- DONE - add in README.md how to compile and run latex sources to generate a .pdf
- DONE - study literature on quantization theory
- DONE - give more structure to the thesis
- DONE - [metrics] clean up
- DONE - [architectures] draft UNet explanation
- DONE - [architectures] draft SRUNet explanation
- DONE - [architectures] draft training setup
- DONE - [optimizations] draft overview optimization techniques
- DONE - [optimizations] draft tensorrt section
- DONE - [experiments] clean up
- DONE - [bureaucracy] website
- DONE - [bureaucracy] ask mighelett'
- DONE - [bureaucracy] ask Emilio
- DONE - [bureaucracy] ask about supervisors
- DONE - [code] add VMAF as quality metric for video
- DONE - [code] train with PNG for ground-truth images
- DONE - [bureaucracy] ask administration about taxes
- DONE - [introduction] make it editable
- DONE - [conclusions] make it editable by the prof
- DONE - [background] make it editable
- DONE - [metrics] explain VMAF
- DONE - [code] run quantitative evaluations
- DONE - [experiments] include new quantitative evaluations
- DONE - [metrics] make it editable
- DONE - [code] re-run timing tests
- DONE - [architectures] make it editable
- DONE - [optimizations] make it editable
- DONE - [code] run VMAF tests
- DONE - [optimizations] draft custom data-loader section
- DONE - put everything you can into English
- DONE - find a quote
- DONE - [abstract] draft an abstract
- DONE - [code] create an image grid, or think of something smart to show qualitative results
- DONE - [experiments] include new qualitative evaluations
- DONE - [experiments] draft qualitative results section
- DONE - [experiments] .4f precicion for speed
- DONE - [experiments] .2f precision for VMAF
- DONE - [experiments] .4f precision for metrics
- DONE - [experiments] arrows to indicate direction of results
- DONE - [experiments] bold best results per column
- DONE - [experiments] put memory size table in the text
- DONE - [abstract] - enhance abstract and translate it in Italian
- DONE - [references] remove not-used references
- DONE - [experiments] put some qualitative results about natural scenes and faces
- DONE - [experiments] - enhance comments on qualitative results
- DONE - [acknowledgement] write acknowledgement
- DONE - ask how long will you have for your thesis dissertation (20 mins including any questions)
- DONE - [metrics] only one example for each category
- DONE - [optimizations] highlight PTQ
- DONE - [experiments] using TensorRT that implements PTQ - remove TensorRT from the optimizations slide
- DONE - [experiments] include dataset description and training 

