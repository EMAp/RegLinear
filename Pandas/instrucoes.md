#Como Executar os Tutoriais

Estes tutoriais estão compostos para execução no [Ipython notebook](http://ipython.org/ipython-doc/stable/interactive/htmlnotebook.html?highlight=notebook).

Para usá-los é necessário instalar os seguintes softwares em um computador com Debian Gnu/Linux ou derivados:

	$ apt-get install python-pip python-numpy python-scipy python-matplotlib
	$ pip install -U pandas ipython statsmodels

Após a instalação, basta digitar no terminal (no mesmo diretório dos notebooks):

	$ ipython notebook --pylab inline 

Este comando deve abrir a interface do notebook no seu navegador onde aparecerão os notebooks prontos para serem usados.