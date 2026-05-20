# Project Planner                    
                                                                                                                                                                                                                      
  A self-contained, single-file Gantt chart project planner that runs entirely in the browser. No build step, no dependencies, no install — just open the page and start planning.                                    
                                                                                                                                                                                                                      
  **Live demo:** https://khalifa168.github.io/gantt-planner/planner.html                                                                                                                                           
                                                                                                                                                                                                                      
  ## Features                                                                                                                                                                                                         
                  
  - **Hierarchical task structure** — PRDs → Stories → Tasks → Milestones                                                                                                                                             
  - **Interactive Gantt chart** with drag-to-schedule and zoomable timeline
  - **Task dependencies** with predecessor links                                                                                                                                                                      
  - **Critical path** highlighting                                                                                                                                                                                    
  - **Resource leveling** to resolve over-allocation automatically                                                                                                                                                    
  - **Progress tracking** with % complete bars and variance indicators                                                                                                                                                
  - **JSON import / export** — your data stays local, version it in git if you like
  - **Keyboard-driven editing** — insert, indent, move, delete rows from the menu or shortcuts                                                                                                                        
  - **Dark UI** modeled after desktop project tools                                                                                                                                                                   
                                                                                                                                                                                                                      
  ## Usage                                                                                                                                                                                                            
                  
  1. Open `planner.html` in any modern browser (or visit the GitHub Pages URL above).                                                                                                                                 
  2. Use **File → New Project** to start fresh, or load a saved `.json` file.
  3. Add rows from the **Edit** menu (PRD / Story / Task / Milestone).                                                                                                                                                
  4. Set durations, start dates, predecessors, and resources directly in the grid.                                                                                                                                    
  5. Use **Project → Recalculate** or **Level Resources** to auto-schedule.                                                                                                                                           
  6. **File → Export JSON** to save your work.                                                                                                                                                                        
                                                                                                                                                                                                                      
  ## Hosting on GitHub Pages                                                                                                                                                                                          
                  
  This repo is already configured to serve `planner.html` as a static site. To enable Pages:                                                                                                                          
  
  1. Go to **Settings → Pages**                                                                                                                                                                                       
  2. Source: **Deploy from a branch**
  3. Branch: `main` / root                                                                                                                                                                                            
  4. The planner will be live at `https://khalifa168.github.io/gantt-planner/planner.html`
                                                                                                                                                                                                                      
  Optionally rename `planner.html` to `index.html` so the root URL works without the filename.                                                                                                                        
                                                                                                                                                                                                                      
  ## Files                                                                                                                                                                                                            
                  
  - `planner.html` — the entire app (HTML + CSS + JS in one file)                                                                                                                                                     
  - `project-2026-04-27.json` — example project file
                                                                                                                                                                                                                      
  ## License      

  MIT                                   
