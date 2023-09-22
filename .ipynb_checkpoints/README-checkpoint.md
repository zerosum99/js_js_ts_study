# js_js_ts_study


# 1. 아나콘다 가상환경 생성 

conda create -n denoJTS python=3.9

conda activate denoJTS

# 2. deno 설치 (맥과 리눅스)

curl -fsSL https://deno.land/x/install/install.sh | sh

# 3. 주피터랩 설치

pip install jupyterlab

# 4. After installation, just run "export" commands shown in terminal:

### Deno was installed successfully to /Users/John/.deno/bin/deno

### Manually add the directory to your $HOME/.zshrc (or similar)

export DENO_INSTALL="/Users/사용자이름/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"

# 5. 주피터랩 실행

jupyter lab