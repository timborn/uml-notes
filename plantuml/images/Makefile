PLANTUML=../plantuml.jar

default: node

node: node2.png

%.png : %.txt
	java -jar $(PLANTUML) $<
