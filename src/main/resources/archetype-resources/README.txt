#set( $symbol_pound = '#' )
#set( $symbol_dollar = '$' )
#set( $symbol_escape = '\' )
mvn archetype:generate ${symbol_escape}
 -DarchetypeGroupId=${package} ${symbol_escape}
 -DarchetypeArtifactId=${artifactId}-archetype ${symbol_escape}
 -DarchetypeVersion=${version} ${symbol_escape}
 -DgroupId=${package} ${symbol_escape}
 -DartifactId=tmp3 ${symbol_escape}