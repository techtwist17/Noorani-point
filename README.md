<!DOCTYPE html><html lang="bn"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover"><title>Maison Store</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600&family=Jost:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#fbfbfa;--pn:#fff;--ink:#1b1f2a;--mut:#6b7080;--ln:#e6e6e2;--acc:#a8873f;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#14161c;--pn:#1c1f27;--ink:#eceae4;--mut:#9a9eab;--ln:#2d313b}}
:root[data-theme="dark"]{--bg:#14161c;--pn:#1c1f27;--ink:#eceae4;--mut:#9a9eab;--ln:#2d313b}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--ink);font:400 15px/1.6 Jost,system-ui,sans-serif}
h1,h2,h3,.logo{font-family:'Cormorant Garamond',Georgia,serif;font-weight:600;margin:0}
button,input,select,textarea{font:inherit;color:inherit}a{color:inherit}
.wrap{max-width:1100px;margin:auto;padding:0 18px}
header{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);border-bottom:1px solid var(--ln);z-index:5}
header .wrap{display:flex;justify-content:space-between;align-items:center;height:62px}
.logo{font-size:26px;letter-spacing:.04em}
.btn{background:var(--ink);color:var(--bg);border:0;padding:10px 20px;cursor:pointer;border-radius:2px}
.btn.o{background:none;color:var(--ink);border:1px solid var(--ink)}.btn.s{padding:5px 11px;font-size:13px}.btn.r{background:#a33;color:#fff}
.btn:focus-visible,input:focus-visible,select:focus-visible,textarea:focus-visible{outline:2px solid var(--acc);outline-offset:2px}
.hero{padding:22px 0 14px;text-align:center;border-bottom:1px solid var(--ln)}
.hero h1{font-size:clamp(26px,5vw,40px);line-height:1.1}.hero p{color:var(--mut);margin:6px 0 0;font-size:14px}
.cats{display:flex;gap:6px;flex-wrap:wrap;padding:14px 0 2px}
.chip{border:1px solid var(--ln);background:none;padding:6px 16px;border-radius:30px;cursor:pointer}.chip.on{background:var(--acc);border-color:var(--acc);color:#fff}
.grid{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;padding:12px 0 40px}
.card{cursor:pointer}.ph{aspect-ratio:1;background:var(--pn);border:1px solid var(--ln);display:flex;align-items:center;justify-content:center;font:600 clamp(26px,6vw,54px) 'Cormorant Garamond',serif;color:var(--acc);overflow:hidden}
.ph img{width:100%;height:100%;object-fit:cover}
.card h3{font-size:clamp(13px,2.2vw,19px);line-height:1.25;margin-top:6px}.price{color:var(--acc);font-weight:500}.mut{color:var(--mut);font-size:13px}
footer{border-top:1px solid var(--ln);padding:26px 0;text-align:center;color:var(--mut);font-size:13px}
.ov{position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:20;display:flex;justify-content:flex-end}
.ov.c{justify-content:center;align-items:center;padding:16px}
.dr{background:var(--bg);width:min(420px,100%);height:100%;overflow:auto;padding:22px;padding-top:calc(22px + env(safe-area-inset-top,0px))}
.md{background:var(--bg);width:min(640px,100%);max-height:92%;overflow:auto;padding:22px}
.row{display:flex;gap:12px;align-items:center;justify-content:space-between;padding:10px 0;border-bottom:1px solid var(--ln)}
input,select,textarea{width:100%;padding:10px;border:1px solid var(--ln);background:var(--pn);border-radius:2px;margin:4px 0 12px}
label{font-size:13px;color:var(--mut)}
.tabs{display:flex;gap:6px;flex-wrap:wrap;padding:14px 0;border-bottom:1px solid var(--ln)}
.tabs .chip{white-space:nowrap}@media(max-width:600px){.wrap{padding:0 10px}.grid{gap:8px}.price{font-size:12px}.chip{padding:5px 11px;font-size:13px}.logo{font-size:22px}}.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:14px;margin:20px 0}
.stat{background:var(--pn);border:1px solid var(--ln);padding:16px}.stat b{display:block;font:600 30px 'Cormorant Garamond',serif}
.tw{overflow-x:auto}table{border-collapse:collapse;width:100%;min-width:480px}td,th{text-align:left;padding:10px 8px;border-bottom:1px solid var(--ln);font-size:14px}