# bigdata-archetype-scala

rm -rf ~/.m2/repository/archetype-catalog.xml

mvn archetype:create-from-project -P windows,\!linux

mvn archetype:update-local-catalog


