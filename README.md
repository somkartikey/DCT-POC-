# DCT-POC
This is my PoC(Proof Of Concept) For Docker-Content-Trust 
....................................................................................................................................
About DCT 
When transferring data between networked systems, especially over the internet, maintaining trust is essential. The main concerns are ensuring that the data hasn't been tampered with (integrity) and verifying who created or sent the data (authenticity). In the Docker ecosystem, when you push (upload) or pull (download) images to or from a Docker registry—whether it's public or private—there's a need to confirm that the data received is exactly what was intended and that it comes from a trusted source.

Docker Content Trust (DCT) addresses this need by enabling digital signatures for Docker images. This means that every image pushed to a Docker registry can be signed by its publisher, and every image pulled from the registry can be verified for its integrity and authenticity. Digital signatures provide a way for Docker clients to check that the images they receive haven't been altered and that they originate from a verified publisher.

DCT supports both manual and automated signing processes. An individual or organization can sign images manually, or the signing can be integrated into an automated software supply chain. This ensures that every image, whether built internally or fetched from external sources, meets the trust criteria, helping to secure the overall software development and deployment process.

.............................................................................................................................................
