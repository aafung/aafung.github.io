SENWEB — local viewer + corpus chat
===================================

1. Unzip this folder.
2. (optional) add a folder  sennet_icons  with flat transparent PNGs:
   brain.png, kupffer_cell.png, p16.png, p21.png, gh2ax.png ...  (missing ones fall back to plain nodes)
3. Serve it:   python3 -m http.server 8000
4. Open http://localhost:8000  (use Chrome/Edge for the AI chat — it needs WebGPU)

Files: index.html, graph_documents.json, graph_hierarchy.json, embeddings.npy,
       rag_chunks.json, rag_vectors.bin.

Chat: click 'Ask the corpus' (bottom-right). Retrieval works on any browser; click 'Enable AI answers'
to download a small local LLM (one-time, ~1-2 GB) for synthesized, cited answers. Citations link to graph nodes.
