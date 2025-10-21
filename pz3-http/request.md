{
	"info": {
		"_postman_id": "9c887df7-d443-4b91-9da2-dcf80a50f15f",
		"name": "TIP03",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "49436946",
		"_collection_link": "https://vlgfoxru-6289832.postman.co/workspace/Max's-Workspace~65ef9be1-9e61-45b4-8b40-07077d8b32bc/collection/49436946-9c887df7-d443-4b91-9da2-dcf80a50f15f?action=share&source=collection_link&creator=49436946"
	},
	"item": [
		{
			"name": "GET /health",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://localhost:8080/health",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8080",
					"path": [
						"health"
					]
				}
			},
			"response": []
		},
		{
			"name": "GET /tasks",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://localhost:8080/tasks",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8080",
					"path": [
						"tasks"
					]
				}
			},
			"response": []
		},
		{
			"name": "POST /tasks",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\"title\":\"БлаБлаБла\"}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "http://localhost:8080/tasks",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8080",
					"path": [
						"tasks"
					]
				}
			},
			"response": []
		},
		{
			"name": "GET /tasks/{id}",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "http://localhost:8080/tasks/2",
					"protocol": "http",
					"host": [
						"localhost"
					],
					"port": "8080",
					"path": [
						"tasks",
						"2"
					]
				}
			},
			"response": []
		}
	]
}