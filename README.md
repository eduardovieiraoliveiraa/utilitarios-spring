# utilitarios-spring



#Capturando a porta e propriedades do servidor no spring: 

import org.springframework.core.env.Environment;

@Autowired
private Environment environment;


#Alterando porta do servidor MS quando copiado a config;
 -> open config -> Arguments -> VM arguments: -Dserver.port=8081


# criando container rabbitmq
docker run -it --name cursomsrabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
