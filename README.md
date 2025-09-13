# Thesis Summary

## Title
**Editing Bengali Scene Text With Style Retention**

## Authors
- Dip Chowdhury (ID: 170104003)  
- Fuad Hasan (ID: 170104010)  
- MD. Abu Yousuf Sajal (ID: 170104025)  
- Syed Rifat Manjur (ID: 170104026)  

**Supervisor:** Mohammad Imrul Jubair  
Department of Computer Science and Engineering  
Ahsanullah University of Science and Technology, Dhaka, Bangladesh  

## Abstract
This thesis addresses the challenge of editing Bengali text in scene images while retaining the original background, font, style, and natural look. Bengali script is particularly complex due to ligatures and conjunct characters, making text manipulation harder compared to English.  

The proposed system consists of three modules:  
1. **Text Conversion Module (TCM):** Transfers text style from a source to a target.  
2. **Background Inpainting Module (BIM):** Removes original text and reconstructs the background.  
3. **Fusion Module (FM):** Combines styled target text with reconstructed background for a natural result.  

To train and evaluate the model, a large Bengali dataset was created:  
- **Synthetic Dataset:** 200,000 examples with ~1.4 million images using 140 fonts and 48,000 Bengali words.  
- **Real-world Dataset:** 400 images collected from street signs, banners, and Google Street View.  

The system uses a modified SRNet model and achieves promising results in both synthetic and real-life scenarios.  

## Contributions
- Developed the **first large-scale Bengali scene text dataset**.  
- Proposed a **modified SRNet model** for Bengali text editing.  
- Demonstrated applications in text removal, correction, hiding sensitive information, and AR-based translation.  

## Results
- Successful editing of synthetic and real-life Bengali text images.  
- Quantitative metrics (MSE, PSNR, SSIM) show competitive performance compared to English text editing models.  
- Identified limitations in handling shadows, curved text, and low-contrast cases.  

## Future Work
- Improve dataset diversity with more complex fonts and real-world scenarios.  
- Extend editing capability to cross-language tasks (Bengali ↔ English).  
- Develop a real-time application for scene text editing and translation.  

## Keywords
Scene Text Editing, Bengali Script, Style Retention, SRNet, Deep Learning, Dataset Generation  

---
📘 **Institution:** Ahsanullah University of Science and Technology  
📅 **Submission Date:** January 2022  
