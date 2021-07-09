# docker-odoo

Installation and debug Odoo ERP in Docker using pycharm

install odoo use docker-compose 

check folder in file docker-compose.yml:

    cd docker-odoo/debug-odoo or cd docker-odoo/odoo11

if you do in folder docker-compose.yml

install like this 

    sudo docker-compose up -d

and then Check:
    
    localhost:1911

Try debug Fungsion:

    import wdb; wdb.set_trace()

restart Docker Container Odoo

    sudo docker restart <name containner odoo>

run logs odoo containner:

    sudo docker logs -f <name containner odoo>

running Odoo on fungsion Odoo

Check debug in 
        
    localhost:1911
