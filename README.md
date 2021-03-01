# spring-boot-microservices-workshop

For post methods

ResponseEntity<String> a = restTemplate.postForEntity("http://localhost:8091/api/assign/test", response,
				String.class);
		
		String id = restTemplate.postForObject("http://localhost:8091/api/assign/test", response,
				String.class);
		
