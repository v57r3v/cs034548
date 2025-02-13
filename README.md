java c
CSEN   338 (4   Units)
Image and Video Compression
PROJECT INFORMATION AND LIST OF SUGGESTED PROJECTS
Phases:
•            Group or individual project
•            Literature survey,   study
•          Design or   Discussion   or   Comparison
•          Implementation   if   any
•            Presentation    Report
Suggested Topics:
1.       Entropy Coding or   Decoding
•          Conduct    a   literature   survey   on   a   fast   entropy   coding   or   decoding   techniques   (e.g.   fast   or   parallel   CABAC decoding or Golomb   decoding).
•          Conduct a simple implementation   (e.g.   software   in   Python/C/Matlab   or hardware   design)   of   a   simple   entropy coder; test it out with images and evaluate your   results   (e.g. memory,   complexity).
•          Do   a presentation and   write   a report.
2.       Predictor or Quantizer   Design
•          Conduct       literature      survey      on      good      predictor/interpolator/filter      techniques      (e.g.      AIF,      Wiener,   directional)   or   good   quantization techniques   (e.g. Lloyd-Max   or others,   cascaded,   adaptive, AQMS,   RDOQ,   subjective).   It   would   be   better   (but   not   critical)   if you   take   into   account   perceptual   visual   distortion, especially for   quantization.
•          Produce      an      implementation      (e.g.    software      in      Python/C/Matlab      or      hardware      design)    of   a      simple predictor or quantizer; test out your work with images.
•          Evaluate   your   results   (e.g. bit-rate   vs. visual   quality   vs.   computational   complexity).
•          Do   a presentation and   write   a report.
3.       2-D Transform
•          Conduct literature   survey   on new   2-D   or   directional   transform   for   image/video   coding.
•          Produce   an   implementation    its   inverse   (e.g. Python/C/Matlab) for   the   transform;   you   can   use   Matlab Image Processing Tool Box; test your transform. with several images with quantization.
•          Evaluate your results (e.g. bit-rate vs. visual   quality   vs.   computational/memory   complexity).
•            Do a presentation and write a report.
4.       Design of a Motion Estimator / Compensator
•          Conduct literature   survey   and   study   on   recent   motion   estimation   techniques.
•          Investigate   one   issue   for   motion   estimation   (e.g.   sub-pel,   AIF   filter,   motion   model,   coding   methods   for MV or residue, reference picture selection/generation, search range, partial distortion   search, MV   competition,flexible search patterns, merge mode, affine methods, motion fields) or advanced motion   methods in HEVC or VVC.
•          Design and produce   a   simple   implementation to   demonstrate   motion   estimation   (e.g.   in   JM   or   HM   or   Matlab/C/Python); test   out   your   design   with   two   or   more   frames.
•          Evaluate your results (e.g. bit-rate vs. visual   quality   vs.   computational/memory   complexity).
•            Do a presentation and write a report.
5.       Performance Analysis for Image Codec
•               Study an image codec structure   of   the   BPG   standard.
•          You can also find out   new   techniques   adopted   in   BPG   that were   not   in   JPEG.
•          Suggest a list of   performance   issues to   evaluate   (e.g.   coding   efficiency,   computational   complexity).
•          Do   a presentation   and write   a report.
6.       Performance Analysis for Video Codec
•          Study      a      video      codec      or   just      decoding.   JVET   VTM   (VVC/H.266)   is   preferred,   but   JCT-VC   HM (HEVC/H.265) or   H.264 JM   arefine. For   some   cases   you   need   to   know   C++. Alternatively, you   could explore   3D   or   scalable   extensions   of   the   codec   (e.g.   JCT-3V   HTM   (3D-HEVC)   software).
•          You can also find   out new techniques   adopted   in   VTM   that were   not   in   HM,   or   in   HM   that   are   not   in   JM; or   comparing two   different codecs.
•          Suggest   a   list   of   performance   issues   to   evaluate   (e.g. coding   efficiency   and   computational   complexity).   Alternatively, you could explore multicore processor or GPUs for   speeding up   codecs.
•          Do   a presentation   and write   a report.
7.       Machine Learning Methods in Video Coding
•          Study   a   video   coding   technique   and   see   which   part(s)   (e.g.   mode   decision,   partitioning/coding   unit   depth   decision,   transform,   intra   prediction,   motion   estimation)   can   machine   learning   methods   (e.g.   SVM,    classification,    decision      trees,    PCA,    sparse      dictionary      learning,    K-SVD)    or      deep      learning methods   (e.g. CNN, GAN, RNN, transformer) be   applied   to   achieve   better   performance.
•          Suggest a list of   performance   issues to   evaluate   (e.g.   coding   efficiency,   computational   complexity).
•          Do   a presentation   and write a report.
8.       Deep Learning Methods in Video Coding
•          I am particularly   interested   in the   study   of   one   of   these methods   for   end-to-end   image/video   coding:
•          (a) Use   of   convolutional neural   network   (CNN)   in   video   coding.
•          (b) Use of   generative   adversarial   network   (GAN)   in   image/video   coding.
•          (c)   Use   of   autoencoder   (AE),   variational   autoencoder   (VAE),   recurrent   neural   network   (RNN),LSTM,   and especially transformers, in image/video   coding.
•            (d) Use of   deep learning approaches in motion estimation.
•            (e) Use of   reinforcement learnin代 写CSEN 338 Image and Video CompressionC/C++
代做程序编程语言g in video rate control.
•          (f) Visual   quality   metric   for   learned   image/video   coding.
•          (g)   Complexity   reduction   methods.
•          Suggest a list of   performance   issues to   evaluate   (e.g.   coding   efficiency,   computational   complexity).
•          Do   a presentation   and write   a report.
9.       A Current Hot Topic (typically   1 person but   can   be   more)   -   Survey /   Study /   Comparison
Select a   recently hot topic of   interest   from:
•          Latest and future JPEG image coding   standards   -   JPEG-AI,   JPEG-DNA,   JPEG-NFT,   JPEG-XE.
•          Latest   and   future   video   coding   standards   - VVC/H.266,NNVC,   etc.
•          Video   coding   for   HDR, WCG,   360 video,   screen   content,   3-D, point   cloud,   etc.
•          Visual   volumetric   video   coding   (V3C) standards   - VPCC, MIV,   V-DMC.
•          Video coding   for   surveillance video.
•          Video   for visually   impaired.
•          Image coding for plenoptic images -   light   field, point cloud,   or holograph.
•          Visual   quality   metric   for   plenoptic   images, 360   video,   3-D   video,   and   point   cloud.
•          Deep learning assisted tools for image/video   coding   (e.g. post-processing,   optimization, rate   control,   reference frame. generation, intra prediction).
•          End-to-end   deep   learning-based   image/video   coding   (e.g.   autoencoder, transformer).
•          Generative AI approaches - GAN, diffusion probabilistic models,   etc.
•          Advanced AI approaches like codebook-based methods, tokenization,   etc.
•          Deep learning in   visual   quality   assessment.
•          Image   or   video   coding   for   machines   (VCM)   (e.g.   semantic   coding,   feature   coding).
•            Green video coding.
•          Advanced      approaches      in      HVS      (e.g.    psycho-visual      studies,      DMOS,      JND,      SSIM,      saliency      map,   reference-free method) and its effect on RDO   and   quantization.
•          Visual   attention   and   saliency.
•          Methods   in   3D   video   coding   (e.g.   depth   coding, view   synthesis,   and   3D-HEVC).
•          Graphics compression (especially 3D   graphics)   or haptic   compression   or AR video.
•          Coding for immersive multimedia,   VR/AR   in   metaverse.
•       Visual communication   (e.g. transcoding, rate   control   or   shaping,   congestion   control)   over   networks.
•          Advanced intra-prediction methods or inter-prediction methods for VVC   or beyond.
•          RDO plus complexity, Lagrange multiplier, or advanced   quantization methods.
•          Pre- or   post-processing   (e.g. artifact   removal,   denoising, or   error   concealment).
•          Computer   vision   approaches   (e.g.   face   detection)   in   coding.
•          Parallel methods and/or use of   GPUs or TPUs   (systolic   arrays)   in   video   coding.
•          Other   advanced   topics   (e.g. super-resolution).
•          Your suggestion (need approval, and must be related to   compression).
         Conduct a literature survey   on   the   topic.
         Study and compare different approaches,   if   needed.
         Do a presentation and write   a report.
10. Your Suggestion
•          Needs   approval.
•          Should    involve      study      or      design,      simple      implementation      or      comparison/evaluation,      report,      and   presentation.
Note: Above are   just suggestions, feel free to modify them   or   suggest your   own   topic   to   suit your projects.
Note: The use of   AI tools   such as   ChatGPT   is   not   allowed.   Copying   materials   from   websites   is   not   allowed   ,   but references are encouraged.
References
1.         The   Internet   and   Web   Sites.
2.       Books recommended on   the   syllabus   and   other related books.
3.       Industrial Magazines   (for more   industrial   oriented projects).
4.       Journals    (IEEE    Transactions      on      Circuits            Systems      for    Video      Technology,      IEEE      Transactions      on   Consumer Electronics, IEEE Transactions on Multimedia, IEEE Transactions on Image Processing, IEEE   Communications,   IEEE   Multimedia,   IEEE   Signal   Processing,   IEEE Networks,   etc.)   (For   more   research   oriented projects).
5.         Conference proceedings.
Report
Suggestion   (but   not   limited   to):
•          Abstract   of   about   50 words
•            Literature survey
•          Design   or Analysis   or   Study
•          Implementation or   Comparison   (if   any)
•          Results   or Presentation   (if   any)
•          Evaluation   or   Comparison
•            Conclusion   (about   20 words)
•          List   of   References   (must)
•          Appendices   (if   any)
It must be a technical   report, not sale’stalk, user’s manual, or layman’stalk.Your   report   must   not   exceed   4 pages   (for   1   person),   6   pages   (group   of   2),   8 pages   (group   of   3),   or   10   pages (group   of   4). For each group project, please   indicate   the   individual   responsible   for   each   portion   of   the   work.   Note that students in the same group may   or may not   receive   the   same   grade.Note also that project result is not   the   most   important   thing.   I   grade   you   based   on   your   effort   and   work,   how   challenging the project is,   and what you have learned.   Please   do not   “copy   and   paste”   materials   from   web   or   other literatures.    Please do not use AI tools   such   as   ChatGPT to   generate   materials   for the report.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
