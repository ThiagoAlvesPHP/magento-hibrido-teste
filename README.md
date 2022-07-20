## Informações Gerais
- Versão Magento: 2.3.6
- PHP 7.3

## Detalhes do Projeto
- Projeto criado do zero
- Criação de novo tema
- Populando projeto com produtos com (bin/magento sampledata:deploy)
- Inserindo Lib Slick.js chamando o JS usando o *requirejs-config.js* e definindo que o mesmo tem como dependência o jquery e chamando o CSS da lib no *Magento_Theme/layout/default_head_blocks.xml*
- Inserindo lib Fontawesome para uso de Icons sendo chamado em *Magento_Theme/layout/default_head_blocks.xml*
- Carousel Topo
Criação de block contendo código HTML chamando o mesmo na Home Page com CMS Static Block Inserindo Widget, Aplicação de **Slick**, CSS: *Magento_Cms/web/css/carousel-top.css* sendo chamado em *Magento_Cms/layout/cms_index_index.xml* tendo como arquivo phtml *Magento_Cms/templates/widget/static_block/default.phtml*
- Apelo Comercial
Criação de block contendo código HTML chamando o mesmo na Home Page com CMS Static Block Inserindo Widget, CSS: *Magento_Cms/web/css/commercial-appeal.css* sendo chamado em *Magento_Cms/layout/cms_index_index.xml*
- Vitrine de Produtos
Widget Catalog New Products List sendo chamado em Home Page tendo como arquivo phtml *Magento_Catalog/templates/product/widget/new/content/new_list.phtml* sendo o mesmo editado para personalização, Aplicação de **Slick**, CSS: *Magento_Catalog/web/css/new_list.css* sendo chama em *Magento_Cms/layout/cms_index_index.xml*
- Grade de Banners
Criação de block contendo código HTML chamando o mesmo na Home Page com CMS Static Block Inserindo Widget, CSS: *Magento_Cms/web/css/grid-banners.css* sendo chamado em *Magento_Cms/layout/cms_index_index.xml*
