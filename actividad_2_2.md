Caso 1 (Startup de micro-interacciones):

HTML/CSS + JavaScript vanilla porque solo requiere render estático. La carga es mínima y no justifica frameworks: menor complejidad = menor sobrecoste arquitectónico. 

Caso 2 (El clon de Figma Corporativo): 

WebAssembly + Rust para procesar millones de vectores con ejecución cercana al nativo y evitar bloqueos del hilo principal. Para la interfaz usa OffscreenCanvas + Web Workers, separando UI . 

Caso 3 (El nuevo Home Baking un Banco Internacional):

TypeScript + Angular por su arquitectura, escalable y mantenible para equipos grandes. En banca prima la robustez: tipado fuerte, módulos, DI y patrones que reducen errores 

