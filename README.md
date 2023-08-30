Organizador de Arquivos por Tipo
Este é um script Python que organiza arquivos em uma pasta com base em suas extensões, movendo-os para pastas específicas correspondentes aos tipos de arquivos.

Pré-requisitos
Certifique-se de ter a biblioteca tkinter instalada para a utilização da função askdirectory, que permite selecionar uma pasta por meio de uma caixa de diálogo.

Você pode instalar o pacote usando o seguinte comando:
pip install tk

Como usar:
Execute o script OrganizadorDeArquivos.py.
Uma caixa de diálogo será exibida para que você selecione a pasta que deseja organizar.
O script analisará todos os arquivos na pasta selecionada e os moverá para subpastas com base em suas extensões.

Estrutura de Pastas
O script organizará os arquivos nas seguintes subpastas, com base em suas extensões:
imagens: Contém arquivos com extensões .png e .jpg.
planilhas: Contém arquivos com extensão .xlsx.
pdfs: Contém arquivos com extensão .pdf.
csv: Contém arquivos com extensão .csv.

Observações:
Certifique-se de que o pacote tkinter esteja instalado para que o script possa funcionar corretamente.
O script considera apenas as extensões mencionadas na estrutura de pastas. Se desejar adicionar ou remover tipos de arquivos, você pode modificar o dicionário locais no código.
Se você já possui pastas com os mesmos nomes da estrutura de pastas no diretório de destino, o script tentará mover os arquivos para essas pastas existentes.
Lembre-se de que este é um script básico e pode não cobrir todos os cenários possíveis de tipos de arquivos. Adaptações adicionais podem ser necessárias para atender a casos específicos.

Nota: Este README é uma descrição geral do funcionamento do script. Certifique-se de personalizá-lo de acordo com suas necessidades e incluir qualquer informação adicional relevante.
