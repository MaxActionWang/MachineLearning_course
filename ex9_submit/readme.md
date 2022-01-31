Please read this file before running the codes.

This zip file contains:

`readme.md`: this document

`report_ex9.pdf`

`Ex9.ipynb`: codes

After running the codes, a `data` directory will be created, and zipped and unzipped CIFAR-10 dataset will be automatically downloaded under this directory.



The environments is based on python3.8& jupyter notebook.

```
# Name                    Version                   Build  Channel
anyio                     3.5.0            py38haa244fe_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
argon2-cffi               21.3.0             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
argon2-cffi-bindings      21.2.0           py38h294d835_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
asttokens                 2.0.5              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
attrs                     21.4.0             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
babel                     2.9.1              pyh44b312d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
backcall                  0.2.0              pyh9f0ad1d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
backports                 1.0                        py_2    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
backports.functools_lru_cache 1.6.4              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
black                     21.12b0            pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
blas                      1.0                         mkl    defaults
bleach                    4.1.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
bottleneck                1.3.2            py38h2a96729_1    defaults
brotli                    1.0.9                ha925a31_2    defaults
brotlipy                  0.7.0           py38h294d835_1003    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
ca-certificates           2021.10.8            h5b45459_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
certifi                   2021.10.8        py38haa244fe_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
cffi                      1.15.0           py38hd8c33c5_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
charset-normalizer        2.0.10             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
click                     8.0.3            py38haa244fe_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
colorama                  0.4.4              pyh9f0ad1d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
cpuonly                   2.0                           0    pytorch
cryptography              36.0.1           py38hb7941b4_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
cycler                    0.11.0             pyhd3eb1b0_0    defaults
dataclasses               0.8                pyhc8e2a94_3    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
debugpy                   1.5.1            py38h885f38d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
decorator                 5.1.1              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
defusedxml                0.7.1              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
entrypoints               0.3             pyhd8ed1ab_1003    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
executing                 0.8.2              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
flit-core                 3.6.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
fonttools                 4.25.0             pyhd3eb1b0_0    defaults
freetype                  2.10.4               hd328e21_0    defaults
icc_rt                    2019.0.0             h0cc432a_1    defaults
icu                       58.2                 ha925a31_3    defaults
idna                      3.1                pyhd3deb0d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
importlib-metadata        4.10.0           py38haa244fe_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
importlib_resources       5.4.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
intel-openmp              2021.4.0          haa95532_3556    defaults
ipykernel                 6.7.0            py38h595d716_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
ipython                   8.0.0            py38haa244fe_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
ipython_genutils          0.2.0                      py_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jedi                      0.18.1           py38haa244fe_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jinja2                    3.0.3              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
joblib                    1.1.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jpeg                      9d                   h2bbff1b_0    defaults
json5                     0.9.5              pyh9f0ad1d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jsonschema                4.4.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyter-client            7.1.0                    pypi_0    pypi
jupyter_client            7.1.1              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyter_core              4.9.1            py38haa244fe_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyter_server            1.13.3             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyterlab                3.2.8              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyterlab_pygments       0.1.2              pyh9f0ad1d_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
jupyterlab_server         2.10.3             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
kiwisolver                1.3.1            py38hd77b12b_0    defaults
libpng                    1.6.37               h2a8f88b_0    defaults
libsodium                 1.0.18               h8d14728_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
libtiff                   4.2.0                hd0e1b90_0    defaults
libuv                     1.43.0               h8ffe710_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
libwebp                   1.2.0                h2bbff1b_0    defaults
lz4-c                     1.9.3                h2bbff1b_1    defaults
m2w64-gcc-libgfortran     5.3.0                         6    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
m2w64-gcc-libs            5.3.0                         7    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
m2w64-gcc-libs-core       5.3.0                         7    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
m2w64-gmp                 6.1.0                         2    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
m2w64-libwinpthread-git   5.0.0.4634.697f757               2    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
markupsafe                2.0.1            py38h294d835_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
matplotlib                3.5.0            py38haa95532_0    defaults
matplotlib-base           3.5.0            py38h6214cd6_0    defaults
matplotlib-inline         0.1.3              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
mistune                   0.8.4           py38h294d835_1005    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
mkl                       2021.4.0           haa95532_640    defaults
mkl-service               2.4.0            py38h2bbff1b_0    defaults
mkl_fft                   1.3.1            py38h277e83a_0    defaults
mkl_random                1.2.2            py38hf11a4ad_0    defaults
mne                       0.24.1                   pypi_0    pypi
msys2-conda-epoch         20160418                      1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
munkres                   1.1.4                      py_0    defaults
mypy_extensions           0.4.3            py38haa244fe_4    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
nbclassic                 0.3.5              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
nbclient                  0.5.10             pyhd8ed1ab_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
nbconvert                 6.4.0            py38haa244fe_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
nbformat                  5.1.3              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
nest-asyncio              1.5.4              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
networkx                  2.6.3              pyhd8ed1ab_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
notebook                  6.4.7              pyha770c72_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
numexpr                   2.8.1            py38hb80d3ca_0    defaults
numpy                     1.21.2           py38hfca59bb_0    defaults
numpy-base                1.21.2           py38h0829f74_0    defaults
olefile                   0.46               pyhd3eb1b0_0    defaults
openssl                   1.1.1l               h8ffe710_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
packaging                 21.3               pyhd3eb1b0_0    defaults
pandas                    1.3.5            py38h6214cd6_0    defaults
pandoc                    2.17                 h8ffe710_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pandocfilters             1.5.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
parso                     0.8.3              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pathspec                  0.9.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
patsy                     0.5.2              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pgmpy                     0.1.17                   py38_0    ankurankan
pickleshare               0.7.5                   py_1003    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pillow                    8.4.0            py38hd45dc43_0    defaults
pip                       21.2.2           py38haa95532_0    defaults
platformdirs              2.4.1                    pypi_0    pypi
prometheus_client         0.12.0             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
prompt-toolkit            3.0.24             pyha770c72_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pure_eval                 0.2.1              pyhd8ed1ab_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pycparser                 2.21               pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pyedflib                  0.1.23                   pypi_0    pypi
pygments                  2.11.2             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pyopenssl                 21.0.0             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pyparsing                 3.0.4              pyhd3eb1b0_0    defaults
pyqt                      5.9.2            py38ha925a31_4    defaults
pyrsistent                0.18.0           py38h294d835_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pysocks                   1.7.1            py38haa244fe_4    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
python                    3.8.12               h6244533_0    defaults
python-dateutil           2.8.2              pyhd3eb1b0_0    defaults
python_abi                3.8                      2_cp38    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
pytorch                   1.10.1              py3.8_cpu_0    pytorch
pytorch-mutex             1.0                         cpu    pytorch
pytz                      2021.3             pyhd3eb1b0_0    defaults
pywin32                   303                      pypi_0    pypi
pywinpty                  0.5.7                    py38_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
pyzmq                     22.3.0           py38h09162b1_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
qt                        5.9.7            vc14h73c81de_0    defaults
requests                  2.27.1             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
scikit-learn              1.0.2                    pypi_0    pypi
scipy                     1.7.3            py38h0a974cb_0    defaults
seaborn                   0.11.2             pyhd3eb1b0_0    defaults
send2trash                1.8.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
setuptools                58.0.4           py38haa95532_0    defaults
sip                       4.19.13          py38ha925a31_0    defaults
six                       1.16.0             pyhd3eb1b0_0    defaults
sniffio                   1.2.0            py38haa244fe_2    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
sqlite                    3.37.0               h2bbff1b_0    defaults
stack-data                0.1.3                    pypi_0    pypi
stack_data                0.1.4              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
statsmodels               0.13.1           py38h6f4d8f0_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
terminado                 0.9.4            py38haa95532_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
testpath                  0.5.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
threadpoolctl             3.0.0                    pypi_0    pypi
tk                        8.6.11               h2bbff1b_0    defaults
tomli                     1.2.3                    pypi_0    pypi
torchaudio                0.10.1                 py38_cpu  [cpuonly]  pytorch
torchvision               0.11.2                 py38_cpu  [cpuonly]  pytorch
tornado                   6.1              py38h2bbff1b_0    defaults
tqdm                      4.62.3             pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
traitlets                 5.1.1              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
typed-ast                 1.5.1            py38h294d835_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
typing_extensions         4.0.1              pyha770c72_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
urllib3                   1.26.8             pyhd8ed1ab_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
vc                        14.2                 h21ff451_1    defaults
vs2015_runtime            14.27.29016          h5e58377_2    defaults
wcwidth                   0.2.5              pyh9f0ad1d_2    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
webencodings              0.5.1                      py_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
websocket-client          1.2.3              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
wheel                     0.37.1             pyhd3eb1b0_0    defaults
win_inet_pton             1.1.0            py38haa244fe_3    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
wincertstore              0.2              py38haa95532_2    defaults
winpty                    0.4.3                         4    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
xz                        5.2.5                h62dcd97_0    defaults
zeromq                    4.3.4                h0e60522_1    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
zipp                      3.7.0              pyhd8ed1ab_0    https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge
zlib                      1.2.11               h8cc25b3_4    defaults
zstd                      1.4.9                h19a0ad4_0    defaults
```







------------------------------

Codes generated with the help of friends and online sources.

王敏行 id：2018012386

wangmx18@mails.tsinghua.edu.cn

