CTRL + Shift + P -> Create a new Jupyter Notebook<br>
Type `python -m venv (venv name)` to make a new venv <br>
Click on top right of ipynb file to link the venv<br>
pip install numpy<2 torch torchvision matplotlib<br>

I'm following this video: https://www.youtube.com/watch?v=8z2oLfK2sIc&t=41s<br>

pip install numpy<2<br>
pip install torch torchvision matplotlib jupyter ipykernel<br>

I was having some sort of problem with numpy 2 ( it was new at the time of me making this )<br>

CUDA wasn't working with default install, so I did this: pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121<br>

this was using my CPU instead of my GPU<br>