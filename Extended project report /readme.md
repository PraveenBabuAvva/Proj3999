# Extended Abstract PROJ3999 (Major Project)  

## **Title:**  
**Low Light Image Enhancement Using Retinex Theory**  

### **Project Supervisor:**  
Dr. Pankaj Kandhway  

### **Cluster Name (AI/ML, VLSI, Comm., CSP, Power Systems):**  
**CS9**  

### **Project Coordinator:**  
Dr. Ambar Bajpai  

---

## **Mini Project (PROJ2999) Outcome:**  
1. Enhanced Brightness and Visibility.  
2. Natural Color Preservation.  
3. Edge Preservation.  
4. Contrast Enhancement.  
5. Output Quality.  

---

## **Extended Project Abstract (up to 300 words):**  
Low illumination images are typically captured in low-light conditions and are often subjected to inconsistent environmental lighting, including overly bright or artificial light. Enhancement results from existing techniques frequently suffer from halo artifacts, unnatural color reproduction, and information loss, limiting their effectiveness. To address these challenges, an algorithm based on a physical lighting model is proposed, which describes the degradation of poorly illuminated images. This model considers environmental light as a pointwise variable that adapts to local light sources. By accurately estimating the model parameters, low illumination images can be directly recovered.  

The proposed algorithm leverages the **Beta Hyperbolic Secant Distribution (BHSD)** to model the dynamic range of pixel intensities effectively. BHSD enhances the estimation of illumination parameters by providing a robust framework for balancing global and local intensity variations. This minimizes errors caused by extreme lighting inconsistencies, improving the precision of the recovered illumination map and leading to enhanced image quality.  

Incorporating **Retinex theory**, the algorithm determines the initial environmental light to obtain the incident component using a Gaussian approach. Next, the environmental light scattering attenuation rate is adjusted based on an information loss constraint to prevent overexposure or underexposure. To suppress halo artifacts and improve edge preservation, a weighted guided filter is employed, with BHSD ensuring smooth intensity transitions while maintaining natural color reproduction.  

Experimental results demonstrate that the algorithm significantly enhances low illumination images across various scenes, improving the visibility of fine details and edge richness. It reproduces colors with greater accuracy, ensuring naturalness and aesthetic quality. This makes the algorithm well-suited for applications in surveillance, photography, and computer vision tasks, where reliable image enhancement is crucial in varying lighting conditions. The proposed method outperforms existing techniques, addressing limitations like halo effects and information loss effectively.  

---

## **Extended Project Objectives (up to 2-4 Bullet Points):**  
1. **Enhance Image Quality in Low-Light Conditions:**  
   Develop an advanced image enhancement algorithm to effectively improve the visibility, edge richness, and natural color reproduction of images captured in challenging low-light environments.  

2. **Minimize Artifacts and Information Loss:**  
   Address common issues in existing techniques, such as halo artifacts, unnatural color rendering, and loss of critical image information, by leveraging a robust physical lighting model and guided refinement techniques.  

---

## **Ghent Chart for Extended Project PROJ3999:**  
# **Project Timeline**

| **Task**                 | **Start Date** | **End Date** | **Duration** |
|--------------------------|----------------|--------------|--------------|
| Consent Form Submission  | 13 Aug         | 21 Aug       | 7 Days       |
| Project Selection        | 2 Aug          | 13 Aug       | 8 Days       |
| Batch Preparation        | 31 Jul         | 2 Aug        | 3 Days       |
| Literature Survey        | 29 Aug         | 29 Aug       | 1 Day        |
| Abstract                 | 21 Aug         | 29 Aug       | 7 Days       |
| Code Development         | 6 Sep          | 25 Sep       | 14 Days      |
| Prepared PPT             | 25 Sep         | 27 Sep       | 2 Days       |
| Prepared Poster          | 27 Sep         | 2 Oct        | 4 Days       |
| Extended Consent Form    | 2 Oct          | 10 Oct       | 7 Days       |

  

---

## **Suggested IEEE Conference Targets:**  
1. 3rd International Conference on Computer, Electronics, Electrical Engineering and Their Applications.  
2. International Conference on Emerging Smart Computing & Informatics 2025.  

---

## **Group Details (Reg No., Name):**  
- **BU21EECE0100149:** Mohammed Ashraf Razvi  
- **BU21EECE0100512:** Shaik Kashida Jabeen  
- **BU21EECE0100527:** Avva Praveen Babu  

---  


