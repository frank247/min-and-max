**Лабораторная работа №6**

**Тема:** Работа с личным git-репозиторием. Отладка программы в VisualStudioCode

Ход работы:

1. Подключить личный git-репозиторий в vscode.

создал и подключил git-репозиторий в vscode

2. Отладить(в коде возможны ошибки, намеренно оставленные преподавателем)программуmax.cpp. Не забывайте комментировать строки программы!!!

прописал и исправил ошибки в коде.

#include<cstdio>

int vector[5]={2,45,34,8,15};

int main()

{

	int i;

	int max=vector[0];

	for(i=1; i<5; i++) {

		if (max<vector[i]) max=vector[i];

	}

	printf("max = %d\n",max);

}


3. Изменить программу так, чтобы осуществлялся поиск минимального значения. Исходный код сохранить в min.cpp

прописал код для осуществления поиска минимального значения.

#include<cstdio>

int vector[5]={2,45,34,8,15};

int main()

{

    int i;
	
    int min=vector[0];

	for(i=1; i<5; i++) {

		if (min>vector[i]) min=vector[i];

	}

	printf("min = %d\n",min);

}

Вывод: прописал код и исправил ошибки так же прописал код для нахождения минимального значения.