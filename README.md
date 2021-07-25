# java



import org.springframework.data.jpa.repository.JpaRepository;
import org.springframework.stereotype.Repository;

@Repository
public interface ContactRepository extends JpaRepository<Contact, Long> {
}
  1  spring-cloud-hello/src/main/resources/application.properties 
@@ -0,0 +1 @@
server.port=${PORT} 
