steps.md

# Instructions to Run InstantMesh and Generate Output

1. **Clone the Repository:**
   - Clone the InstantMesh repository from GitHub:
     ```bash
     git clone https://github.com/TencentARC/InstantMesh
     cd InstantMesh
     ```

2. **Install Dependencies:**
   - Install the required dependencies using pip:
     ```bash
     pip install -r requirements.txt
     ```

3. **Download Pretrained Model:**
   - Download the pretrained model from the Hugging Face model hub:
     ```bash
     hf_hub_download TencentARC/InstantMesh
     ```

4. **Run the Code:**
   - Execute the main script to generate 3D mesh from a single image:
     ```bash
     python run.py
     ```

5. **View the Output:**
   - Once the code execution is complete, you can find the generated 3D mesh output in the specified directory.

6. **Citation:**
   - If you use InstantMesh in your work, don't forget to cite the paper:
     ```BibTeX
     @article{xu2024instantmesh,
       title={InstantMesh: Efficient 3D Mesh Generation from a Single Image with Sparse-view Large Reconstruction Models},
       author={Xu, Jiale and Cheng, Weihao and Gao, Yiming and Wang, Xintao and Gao, Shenghua and Shan, Ying},
       journal={arXiv preprint arXiv:2404.07191},
       year={2024}
     }
     ```
     