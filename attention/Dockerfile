FROM vllm/vllm-openai:v0.11.0

COPY ./vllm/entrypoints/openai/serving_responses.py /usr/local/lib/python3.12/dist-packages/vllm/entrypoints/openai/serving_responses.py
COPY ./vllm/outputs.py /usr/local/lib/python3.12/dist-packages/vllm/outputs.py
COPY ./vllm/sampling_params.py /usr/local/lib/python3.12/dist-packages/vllm/sampling_params.py
COPY ./vllm/entrypoints/openai/protocol.py /usr/local/lib/python3.12/dist-packages/vllm/entrypoints/openai/protocol.py
COPY ./vllm/v1/core/sched/scheduler.py /usr/local/lib/python3.12/dist-packages/vllm/v1/core/sched/scheduler.py
COPY ./vllm/v1/engine/__init__.py /usr/local/lib/python3.12/dist-packages/vllm/v1/engine/__init__.py
COPY ./vllm/v1/engine/output_processor.py /usr/local/lib/python3.12/dist-packages/vllm/v1/engine/output_processor.py
COPY ./vllm/v1/worker/gpu_model_runner.py /usr/local/lib/python3.12/dist-packages/vllm/v1/worker/gpu_model_runner.py
