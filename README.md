<h1>Інструкція:</h1>

1. Завантажте скріпт командою $wget https://raw.githubusercontent.com/tkachovua/kubeplugin/main/scripts/kubeplugin

2. Зробіть файл виконуванним командою $chmod +x ./kubeplugin 

3. Переіменуйте файл в kubectl-kubeplugin і перемістить в /usr/local/bin/ командою $sudo mv ./kubeplugin /usr/local/bin/kubectl-kubeplugin

4. Перевірте доступність плагіну командою: $kubectl plugin list

5. Запустіть плагін командою: $kubectl kubeplugin pods kube-system - де kube-system це бажаний namespace, а pods це тип ресурсу.