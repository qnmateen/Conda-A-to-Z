# Basic Commands   

**create a environment**    

usage: conda create [-h] [--clone ENV] [-n ENVIRONMENT | -p PATH] [-c CHANNEL]
                    [--use-local] [--override-channels]
                    [--repodata-fn REPODATA_FNS] [--strict-channel-priority]
                    [--no-channel-priority] [--no-deps | --only-deps]
                    [--no-pin] [--copy] [-C] [-k] [--offline] [-d] [--json]
                    [-q] [-v] [-y] [--download-only] [--show-channel-urls]
                    [--file FILE] [--no-default-packages] [--dev]
                    [package_spec [package_spec ...]]
   
conda create --name myenv   

conda create --name myenv python3.9. 

**activate conda environmnet**  

conda activate myenv  

**List installed packages in an environment**  

conda list --name $environment_name   

**list of environment***   

conda env list  

conda info --envs  
 
**conda install package**   

conda install package name

conda install -c bioconda multiqc  

**update package**  

conda update --name $ENVIRONMENT_NAME $PACKAGE_NAME  

conda update python  

**update package manager**  

conda remove --name $ENVIRONMENT_NAME $PACKAGE_NAME  

**deactivate a environment**  

conda deactivate  

**Search available packages**  

conda search $search_term  

**Install other package manager**  

conda install pip  


