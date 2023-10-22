Tabela "azure_company employee"
deletei a coluna "azure_company.departament"
deletei a coluna "azure_company.dependent"
deletei a coluna "azure_company.employee(Ssn)"
deletei a coluna "azure_company.employee(Super_ssn)"
deletei a coluna "azure_company.works_on"
deletei a coluna "azure_company works_on"
renomeei a coluna "Dno" para "Dnumber"
mesclei as colunas "Fname" e "Minit" nomeando a nova coluna como "Name"
mesclei as colunas "Name" e "Lname" nomeando a nova coluna como "Name"
alterei o tipo de "salary" para Número decimal fixo
atribuí o Super_ssn:888665555 à "james E. Borg"
mesclei as tabelas "Employee" e "Department"
deletei a coluna "Super_ssn"
deletei a coluna "Dnumber"
deletei a coluna "Department.azure_company.dept_locations"
deletei a coluna "Department.azure_company.employee"
deletei a coluna "Department.azure_company.project"
separei o número do endereço da coluna "Adress" criando as colunas "Adress number" e "Adress"
separei o número do endereço da coluna "Adress" criando as colunas "Adress" e "State"
separei o número do endereço da coluna "Adress" criando as colunas "Adress" e "City"
renomeei a coluna "Department.Dname" para "Department Name"
renomeei a coluna "Department.Dnumber" para "Department Number"


Tabela "azure_company departament"
tabela renomeada para "Department"
realizei a mescla das tabelas "company departament" e "dept_location"
realizei a remoção da coluna "azure_company dept_locations.Dnumber
renomeei a coluna "azure_company dept_locations.Dlocation" para "Dlocation"
mesclei as colunas "Dname" e "Dlocation" nomeando a nova coluna como "Department"
deletei a coluna "azure_company.dept_locations"
deletei a coluna "azure_company dept_locations.azure_company.departament"
renomeei a coluna "Mgr_ssn" para "manager_ssn"
deletei a coluna "Dept_create_date"
deletei a coluna "azure_company.employee"
deletei a coluna "azure_company.project"
desabilitei a carga desta tabela

Tabela "azure_company dept_locations"
tabela renomeada para "Dept_Locations"
deletei a coluna "azure_company.departament"
desabilitei a carga desta tabela

Tabela ""azure_company project"
tabela renomeada para "Project"
coluna "Dnum" renomeada para "Dnumber"
deletei a coluna "azure_company.departament"
deletei a coluna "azure_company.works_on"

Tabela "azure_company works_on"
tabela renomeada para "Works_On"
deletei a coluna"azure_company.employee"
deletei a coluna "azure_company.project"

Tabela "azure_company dependent"
tabela renomeada para "Dependent"
deletei a coluna "azure_company.employee"

criei a tabela "Store" com as colunas "Store", "Dnumber" e "Mgr_ssn" para uso futuro em criação de tabelas

resposta do ponto 14: se for atribuído e não mesclado as linhas não irão coincidir, gerando várias linhas extras com atributos null
