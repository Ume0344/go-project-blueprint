package main

import (
	"fmt"
	"log"
	"net/http"
	"os"
)

func healthzHandler(w http.ResponseWriter, r *http.Request) {
	w.WriteHeader(http.StatusOK)
	_, _ = w.Write([]byte("Successfully connected to the Go project!"))
}

func main() {
	port := os.Getenv("PORT")
	if port == "" {
		port = "8080"
	}

	http.HandleFunc("/healthz", healthzHandler)

	// http://localhost:8080/healthz
	fmt.Printf("🚀 Starting server on port %s\n", port)
	log.Fatal(http.ListenAndServe(":"+port, nil))
}
