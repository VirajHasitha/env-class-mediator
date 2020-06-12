# env-class-mediator

The env-class-mediator can be used to read the environment variables and set them into a message property.

### How to use the env-class-mediator in the mediation

 <class name="org.wso2.ei.sample.EnvClassMediator">
    <property name="envVarName" value="JAVA_HOME"/>
 </class>
 <log level="custom">
    <property expression="get-property('envVarValue')" name="ReadEnvVariableFromClassMediator"/>
 </log>
