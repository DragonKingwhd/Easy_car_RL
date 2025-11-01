# Easy_car_RL
just_test
1. 首先安装项目
python -m pip install -e source/car
2. 检查环境是否正确注册
python scripts/list_envs.py
3. 测试环境（使用随机动作）
python scripts/random_agent.py --task=Template-Car-v0
4. 开始训练
python scripts/rsl_rl/train.py --task=Template-Car-v0
python scripts/rsl_rl/train.py --task=Template-Car-v0 --num_envs 4 
python scripts/rsl_rl/train.py --task=Template-Car-v0 --headless
继续上次训练：
python scripts/rsl_rl/play.py --task=Template-Car-v0 --num_envs 16
测试环境
