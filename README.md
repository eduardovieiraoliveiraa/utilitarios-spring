# utilitarios-spring



#Capturando a porta e propriedades do servidor no spring: 

import org.springframework.core.env.Environment;

@Autowired
private Environment environment;


#Alterando porta do servidor MS quando copiado a config;
 -> open config -> Arguments -> VM arguments: -Dserver.port=8081
