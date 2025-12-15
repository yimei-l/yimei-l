# 克隆你的仓库到本地（如果还没克隆）
git clone https://github.com/yimei-l/yimei-l.git
cd yimei-l

# 创建所有文件夹
mkdir -p .github/workflows \
         assets/{images,docs} \
         projects/masters-thesis/{data/{raw,processed},models/{times,cge},analysis,lca,outputs,docs} \
         tools/{energy-data-processor,gis-analysis,visualization} \
         publications \
         presentations \
         tests

# 验证创建结果
find . -type d | sort
