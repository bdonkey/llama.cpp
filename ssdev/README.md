<!-- markdownlint-disable MD046 MD041 MD013 MD034-->

# Quick Run

- download https://huggingface.co/TheBloke/Llama-2-13B-GGUF/blob/main/llama-2-13b.Q5_K_M.gguf to ` /Users/scottschmidt/scottdev/mlModelRepos/llama-2-13b.Q5_K_M.gguf `
- run ` make -j && ./main -m /Users/scottschmidt/scottdev/mlModelRepos/llama-2-13b.Q5_K_M.gguf -p "Building a website can be done in 10 simple steps:\nStep 1:" -n 400 -e `
- 