# Pre-selector
<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-title" content="粉体选型">
<meta name="theme-color" content="#f2f2f7" media="(prefers-color-scheme:light)">
<meta name="theme-color" content="#000" media="(prefers-color-scheme:dark)">
<title>粉体设备预选型</title>
<style>
  :root{
    --bg:#f2f2f7; --card:#fff; --text:#000; --sub:#8a8a8e;
    --line:rgba(60,60,67,.12); --accent:#007aff; --danger:#ff3b30;
    --fill:rgba(120,120,128,.12);
  }
  @media (prefers-color-scheme:dark){
    :root{
      --bg:#000; --card:#1c1c1e; --text:#fff; --sub:#8e8e93;
      --line:rgba(255,255,255,.13); --accent:#0a84ff; --danger:#ff453a;
      --fill:rgba(120,120,128,.24);
    }
  }
  *{box-sizing:border-box;-webkit-tap-highlight-color:transparent;}
  html,body{margin:0;padding:0;}
  body{
    background:var(--bg); color:var(--text); min-height:100vh;
    font-family:-apple-system,BlinkMacSystemFont,"SF Pro Text","PingFang SC","Helvetica Neue",sans-serif;
    -webkit-font-smoothing:antialiased;
    padding:calc(env(safe-area-inset-top) + 22px) 16px calc(env(safe-area-inset-bottom) + 40px);
  }
  .wrap{max-width:520px;margin:0 auto;}

  .hd{padding:0 4px 18px;}
  .hd h1{margin:0;font-size:27px;font-weight:700;letter-spacing:-.02em;}
  .hd p{margin:6px 0 0;font-size:13px;font-weight:500;color:var(--sub);}

  .card{
    background:var(--card); border-radius:18px; overflow:hidden;
    box-shadow:0 1px 2px rgba(0,0,0,.05), 0 10px 30px rgba(0,0,0,.05);
    margin-bottom:14px;
  }
  @media (prefers-color-scheme:dark){ .card{box-shadow:none;} }

  .row{padding:13px 18px;}
  .row + .row{border-top:1px solid var(--line);}
  .lbl{display:block;font-size:13px;font-weight:600;color:var(--sub);margin-bottom:3px;}
  .row input, .row select{
    display:block;width:100%;padding:4px 0;border:0;outline:0;background:transparent;
    color:var(--text);font-family:inherit;font-size:17px;font-weight:600;
    -webkit-appearance:none;appearance:none;
  }
  .row input::placeholder{color:var(--sub);opacity:.4;font-weight:500;}
  .row select{cursor:pointer;}
  .row select option{background:var(--card);color:var(--text);}

  /* 分段控件 */
  .seg{display:flex;gap:4px;padding:0 18px 16px;}
  .seg button{
    flex:1;padding:9px 0;border:0;border-radius:9px;background:var(--fill);
    color:var(--text);font-family:inherit;font-size:14px;font-weight:600;cursor:pointer;
    transition:background .15s,color .15s;
  }
  .seg button.on{background:var(--accent);color:#fff;}

  /* 标签 */
  .chips{display:flex;flex-wrap:wrap;gap:8px;padding:4px 18px 18px;}
  .chip{
    padding:8px 12px;border-radius:10px;border:0;background:var(--fill);
    color:var(--text);font-family:inherit;font-size:13px;font-weight:500;cursor:pointer;
    transition:background .15s,color .15s;
  }
  .chip.on{background:var(--accent);color:#fff;}

  /* 按钮 */
  .go{
    display:block;width:100%;padding:17px;border:0;border-radius:16px;
    background:var(--accent);color:#fff;font-family:inherit;
    font-size:17px;font-weight:700;letter-spacing:.01em;cursor:pointer;
    margin:4px 0 22px;
  }
  .go:active{opacity:.82;}

  /* 结果 */
  .res-head{
    display:flex;align-items:center;gap:8px;padding:0 4px 10px;
    font-size:13px;font-weight:600;color:var(--sub);letter-spacing:.02em;
  }
  .main{padding:20px 18px 18px;}
  .badge{
    display:inline-block;padding:4px 9px;border-radius:7px;
    background:color-mix(in srgb, var(--accent) 15%, transparent);
    color:var(--accent);font-size:11px;font-weight:700;letter-spacing:.04em;
    margin-bottom:10px;
  }
  .main h2{margin:0;font-size:22px;font-weight:700;letter-spacing:-.02em;}
  .main .sub{margin:5px 0 16px;font-size:13px;font-weight:500;color:var(--sub);}
  .grid{display:grid;grid-template-columns:1fr 1fr;gap:14px 12px;}
  .grid > div{min-width:0;}
  .grid span{display:block;font-size:11px;font-weight:600;color:var(--sub);letter-spacing:.04em;margin-bottom:3px;}
  .grid b{display:block;font-size:16px;font-weight:600;letter-spacing:-.01em;}
  .opt{margin-top:16px;padding-top:14px;border-top:1px solid var(--line);font-size:13px;color:var(--sub);line-height:1.5;}
  .opt b{color:var(--text);font-weight:600;}

  .alt{padding:15px 18px;}
  .alt + .alt{border-top:1px solid var(--line);}
  .alt h3{margin:0;font-size:16px;font-weight:600;letter-spacing:-.01em;}
  .alt p{margin:4px 0 0;font-size:13px;color:var(--sub);font-weight:500;}
  .alt .kv{margin-top:8px;display:flex;gap:16px;flex-wrap:wrap;font-size:13px;font-variant-numeric:tabular-nums;}
  .alt .kv span{color:var(--sub);}
  .alt .kv b{font-weight:600;}

  .empty{padding:26px 18px;text-align:center;}
  .empty h3{margin:0 0 6px;font-size:17px;font-weight:600;}
  .empty p{margin:0;font-size:13px;color:var(--sub);line-height:1.6;}

  .tip{
    margin-top:16px;padding:0 4px;
    font-size:12px;color:var(--sub);line-height:1.6;
  }
  .hidden{display:none;}
</style>
</head>
<body>
<div class="wrap">

  <header class="hd">
    <h1>粉体设备预选型</h1>
    <p>输入物料与工艺要求，输出设备建议</p>
  </header>

  <!-- 物料 -->
  <section class="card">
    <div class="row">
      <label class="lbl">物料名称</label>
      <input id="mat" type="text" placeholder="选填，如 碳酸钙" autocomplete="off" spellcheck="false">
    </div>
    <div class="row">
      <label class="lbl">物料类别</label>
      <select id="cat">
        <option value="">请选择</option>
        <option value="mineral">非金属矿（碳酸钙、高岭土、滑石等）</option>
        <option value="hard">硬质矿物（石英、碳化硅、刚玉）</option>
        <option value="battery">电池材料（正 / 负极）</option>
        <option value="pharma">医药 / 原料药</option>
        <option value="food">食品 / 保健品</option>
        <option value="chem">化工 / 颜料 / 染料</option>
        <option value="herb">中药 / 植物纤维</option>
        <option value="metal">金属粉末</option>
        <option value="waste">固废 / 粉煤灰 / 钢渣</option>
        <option value="other">其他</option>
      </select>
    </div>
    <div class="row">
      <label class="lbl">目标产能（kg/h）</label>
      <input id="cap" type="text" inputmode="decimal" placeholder="如 500" autocomplete="off">
    </div>
  </section>

  <!-- 粒度 -->
  <section class="card">
    <div class="row">
      <label class="lbl">目标粒度（µm）</label>
      <input id="size" type="text" inputmode="decimal" placeholder="如 10" autocomplete="off">
    </div>
    <div class="seg" id="seg">
      <button data-v="D50">D50</button>
      <button data-v="D90">D90</button>
      <button data-v="D97" class="on">D97</button>
      <button data-v="D99">D99</button>
    </div>
  </section>

  <!-- 工艺要求 -->
  <section class="card">
    <div class="row">
      <label class="lbl">工艺要求（可多选）</label>
    </div>
    <div class="chips" id="chips">
      <button class="chip" data-k="hard">莫氏硬度 &gt; 5</button>
      <button class="chip" data-k="heat">热敏 / 低熔点</button>
      <button class="chip" data-k="wet">含水率 &gt; 10%</button>
      <button class="chip" data-k="ex">易燃易爆</button>
      <button class="chip" data-k="fib">纤维状 / 高韧性</button>
      <button class="chip" data-k="sticky">粘性强</button>
      <button class="chip" data-k="sugar">含糖 / 含油 / 高脂</button>
      <button class="chip" data-k="pure">要求无金属污染</button>
      <button class="chip" data-k="gmp">医药 / 食品 GMP</button>
      <button class="chip" data-k="soft">团聚体需打散</button>
    </div>
  </section>

  <button class="go" id="go">开始评估</button>

  <div id="out"></div>

  <p class="tip">结果基于标准工况估算。实际产能与物料硬度、水分、粒度分布密切相关，建议寄料至实验室做小试确认。</p>

</div>

<script>
/* ============ 设备库 ============ */
const DB = [
  {
    id:'MQW', name:'MQW 流化床式气流磨', sub:'卧式分级轮 · 干法超细',
    cat:'气流磨', d97:[3,45], r50:[1,25],
    good:['heat','pure','ex','gmp','ultra'],
    bad:['fib','sticky'],
    models:[
      ['MQW03',0.3,1],['MQW06',10,30],['MQW10',20,300],['MQW20',40,600],
      ['MQW30',100,900],['MQW40',200,1200],['MQW60',500,2000],
      ['MQW80',800,3000],['MQW100',1000,4000],['MQW120',1500,6000],
      ['MQW160',2000,8000],['MQW240',4000,12000]
    ],
    opt:['氮气循环保护','陶瓷内衬','CIP / SIP','防爆设计']
  },
  {
    id:'MQL', name:'MQL 流化床式气流磨', sub:'立式单转子 · 大产能',
    cat:'气流磨', d97:[6,150], r50:[2,45],
    good:['heat','pure','ex','gmp'],
    bad:['fib','sticky'],
    models:[
      ['MQL03',10,40],['MQL06',10,60],['MQL10',20,300],['MQL20',40,600],
      ['MQL30',100,900],['MQL40',200,1200],['MQL50',500,2000],
      ['MQL80',800,3000],['MQL100',1000,4000],['MQL120',1500,6000],
      ['MQL160',2000,8000],['MQL240',4000,12000]
    ],
    opt:['氮气循环保护','陶瓷内衬','称重喂料','防爆设计']
  },
  {
    id:'MQP', name:'MQP 圆盘式气流磨', sub:'无传动 · 结构简单',
    cat:'气流磨', d97:[5,45], r50:[1.5,45],
    good:['pure','ex'],
    bad:['sticky','fib','heat'],
    models:[
      ['MQP01',0.02,0.1],['MQP02',0.2,2],['MQP03',1,10],['MQP06',5,30],
      ['MQP10',10,200],['MQP20',50,500],['MQP30',100,800],
      ['MQP40',200,1000],['MQP60',500,2000],['MQP80',1000,3000],
      ['MQP100',4000,6000]
    ],
    opt:['陶瓷内衬','CIP / SIP','氮气循环保护']
  },
  {
    id:'MQPV', name:'MQPV 圆盘式气流磨', sub:'内置分级轮 · 切割精度高',
    cat:'气流磨', d97:[4,60], r50:[1.5,25],
    good:['pure','ex','gmp'],
    bad:['fib','sticky'],
    models:[
      ['MQPV06',10,200],['MQPV10',20,400],['MQPV15',50,800],
      ['MQPV20',150,1500],['MQPV40',300,2000]
    ],
    opt:['陶瓷内衬','氮气循环保护','GMP 结构']
  },
  {
    id:'STEAM', name:'S-MQW/L 蒸汽动能磨', sub:'过热蒸汽 · 亚微米级',
    cat:'蒸汽磨', d97:[1.5,45], r50:[0.5,16],
    good:['heat','pure','ultra','wet'],
    bad:['fib'],
    models:[
      ['S-MQW/L 2000',400,1000],['S-MQW/L 3000',600,1500],
      ['S-MQW/L 4000',800,2000],['S-MQW/L 6000',1200,3000],
      ['S-MQW/L 10000',2000,5000],['S-MQW/L 15000',3000,8000],
      ['S-MQW/L 20000',4000,10000]
    ],
    opt:['陶瓷内衬','多级分级串联','防爆设计']
  },
  {
    id:'CSMV', name:'CSM-V 空气分级磨', sub:'立式分级轮 · 通用型',
    cat:'机械磨', d97:[5,115], r50:[2,45],
    good:['soft'],
    bad:['pure','fib'],
    models:[
      ['CSM280-V',60,150],['CSM350-V',120,280],['CSM410-V',180,380],
      ['CSM510-V',260,520],['CSM710-V',400,760],['CSM760-V',450,850],
      ['CSM900-V',700,1300],['CSM1000-V',850,1500],['CSM1100-V',1100,2000],
      ['CSM1250-V',1500,2600],['CSM1500-V',2000,3400],['CSM2000-V',3000,5200]
    ],
    opt:['陶瓷内衬','低温 / 惰性气体循环','防爆设计']
  },
  {
    id:'CSMH', name:'CSM-H 空气分级磨', sub:'卧式分级轮 · 超细',
    cat:'机械磨', d97:[4,38], r50:[1.5,15],
    good:['soft','heat'],
    bad:['pure','fib'],
    models:[
      ['CSM280-H',40,100],['CSM400-H',90,220],['CSM510-H',150,360],
      ['CSM630-H',240,560],['CSM710-H',340,800],['CSM1000-H',700,1600],
      ['CSM1250-H',1100,2400],['CSM1500-H',1600,3400]
    ],
    opt:['陶瓷内衬','低温粉碎','防爆设计']
  },
  {
    id:'CSMVD', name:'CSM-VD 空气分级磨', sub:'双轴合一 · 医药食品级',
    cat:'机械磨', d97:[5,115], r50:[2,45],
    good:['gmp','pure','soft'],
    bad:['fib','hard'],
    models:[
      ['CSM280-VD',30,80],['CSM350-VD',55,140],['CSM450-VD',90,220],
      ['CSM510-VD',130,320],['CSM710-VD',220,560],['CSM900-VD',400,1000],
      ['CSM1100-VD',650,1600]
    ],
    opt:['CIP / SIP','陶瓷内衬','GMP 验证文件']
  },
  {
    id:'CSMHJ', name:'CSM-HJ 空气分级磨', sub:'低成本通用',
    cat:'机械磨', d97:[8,115], r50:[3,45],
    good:['soft'],
    bad:['pure','fib','gmp'],
    models:[
      ['CSM500-HJ',160,400],['CSM600-HJ',240,600],['CSM800-HJ',400,1000],
      ['CSM1000-HJ',650,1600],['CSM1250-HJ',1000,2600],['CSM1500-HJ',1600,4000]
    ],
    opt:['陶瓷内衬','防爆设计']
  },
  {
    id:'CUMP', name:'CUM-P 针盘磨', sub:'无筛网 · 出料流畅',
    cat:'机械磨', d97:[25,115], r50:[10,45],
    good:['fib'],
    bad:['pure','sticky','hard'],
    models:[
      ['CUM160-P',30,80],['CUM250-P',90,240],['CUM360-P',180,480],
      ['CUM500-P',350,950],['CUM630-P',600,1600],['CUM800-P',950,2600],
      ['CUM1000-P',1500,4000]
    ],
    opt:['双动力 200m/s','陶瓷内衬','惰性气体循环']
  },
  {
    id:'CUMF', name:'CUM-F 锤式磨', sub:'筛网控制 · 粗粉',
    cat:'机械磨', d97:[25,2000], r50:[10,850],
    good:['fib','soft'],
    bad:['pure','hard','gmp'],
    models:[
      ['CUM160-F',60,200],['CUM250-F',180,500],['CUM360-F',350,900],
      ['CUM500-F',700,1800],['CUM630-F',1200,3000],['CUM800-F',2000,5000],
      ['CUM1000-F',3500,8000]
    ],
    opt:['陶瓷内衬','防爆设计','加热 / 冷却风']
  },
  {
    id:'ULM', name:'ULM 转子磨', sub:'多层刀片 · 韧性物料',
    cat:'机械磨', d97:[8,115], r50:[3,45],
    good:['fib','soft'],
    bad:['hard','pure'],
    models:[
      ['ULM400',60,150],['ULM600',150,380],['ULM800',300,750],
      ['ULM1000',550,1300],['ULM1200',800,2000],['ULM1500',1300,3200]
    ],
    opt:['低温粉碎','陶瓷内衬','防爆设计']
  },
  {
    id:'RTM', name:'RTM 涡流磨', sub:'锥形转子 · 低升温',
    cat:'机械磨', d97:[2.5,600], r50:[1,250],
    good:['fib','soft','sticky'],
    bad:['hard','pure'],
    models:[
      ['RTM300',80,200],['RTM500',240,600],['RTM750',500,1200],
      ['RTM1000',800,1900],['RTM1250',1100,2600],['RTM1500',1600,3800]
    ],
    opt:['陶瓷内衬','防爆设计','外接热源改性']
  },
  {
    id:'MZ', name:'MZ 振动磨', sub:'研磨介质 · 中药专用可选',
    cat:'机械磨', d97:[6,380], r50:[2.5,150],
    good:['fib','hard','soft'],
    bad:['pure'],
    models:[
      ['MZ100',100,200],['MZ300',200,300],['MZ500',300,600],
      ['MZ600',400,800],['MZ800',500,1000],['MZ1000',800,1500],
      ['MZ1200',1000,1800],['MZ2000',2000,3000]
    ],
    opt:['陶瓷磨介','低温 / 水冷夹套','GMP 结构']
  },
  {
    id:'BALL', name:'球磨分级生产线', sub:'大规模 · 低成本',
    cat:'球磨', d97:[3,45], r50:[1.5,20],
    good:['hard','wet'],
    bad:['heat','gmp'],
    models:[
      ['IBM1830 线',1000,3000],['IBM2200 线',2000,5000],
      ['IBM2400 线',3000,8000],['IBM2600 线',5000,12000],
      ['IBM2800 线',7000,16000],['IBM3000 线',9000,20000]
    ],
    opt:['陶瓷衬板','多级分级串联','自动包装码垛']
  }
];

/* ============ 物料类别 → 默认属性 ============ */
const CAT_ATTRS = {
  mineral: [],
  hard:    ['hard','pure'],
  battery: ['pure','ex'],
  pharma:  ['gmp','pure','heat'],
  food:    ['gmp','sugar'],
  chem:    ['heat'],
  herb:    ['fib','heat'],
  metal:   ['ex','pure','hard'],
  waste:   ['hard','wet'],
  other:   []
};

/* ============ 交互 ============ */
const $ = id => document.getElementById(id);
const matEl  = $('mat'),  catEl  = $('cat'),  capEl = $('cap');
const sizeEl = $('size'), segEl  = $('seg'),  chipsEl = $('chips');
const outEl  = $('out');

let basis = 'D97';

segEl.addEventListener('click', e => {
  const b = e.target.closest('button');
  if(!b) return;
  [...segEl.children].forEach(x => x.classList.remove('on'));
  b.classList.add('on');
  basis = b.dataset.v;
});

chipsEl.addEventListener('click', e => {
  const b = e.target.closest('.chip');
  if(!b) return;
  b.classList.toggle('on');
});

catEl.addEventListener('change', () => {
  const def = CAT_ATTRS[catEl.value] || [];
  [...chipsEl.children].forEach(b => {
    b.classList.toggle('on', def.includes(b.dataset.k));
  });
});

/* ============ 计算 ============ */
function normD97(size, basis){
  if (basis === 'D50') return size * 2.5;
  if (basis === 'D90') return size * 1.4;
  if (basis === 'D99') return size * 1.1;
  return size;
}

function scoreSeries(s, d97, cap, attrs){
  // 硬度硬约束：机械磨不适合莫氏 > 5
  if (attrs.includes('hard') && s.cat === '机械磨') return -1;
  // 含水高：气流磨除非蒸汽磨
  if (attrs.includes('wet') && s.cat === '气流磨') return -1;

  // 粒度可达性
  if (d97 < s.d97[0] * 0.65) return -1;
  if (d97 > s.d97[1] * 2.2) return -1;

  let sc = 0;

  // 粒度分
  if (d97 >= s.d97[0] && d97 <= s.d97[1]) sc += 60;
  else if (d97 < s.d97[0]) sc += 15;
  else sc += 20 - Math.min(20, (d97 - s.d97[1]) / s.d97[1] * 30);

  // 产能分
  const maxCap = s.models[s.models.length - 1][2];
  if (cap > maxCap * 5) return -1;
  sc += cap <= maxCap ? 30 : 8;

  // 属性分
  for (const a of attrs){
    if (s.good.includes(a)) sc += 16;
    if (s.bad.includes(a))  sc -= 24;
  }

  // 工艺取向
  if (s.cat === '气流磨' && d97 > 40) sc -= 18;
  if (s.cat === '机械磨' && d97 < 8)  sc -= 22;

  return sc;
}

function pickModel(s, cap){
  for (const m of s.models){
    if (m[2] >= cap) return { name:m[0], range:`${m[1]}–${m[2]} kg/h` };
  }
  const last = s.models[s.models.length - 1];
  const k = Math.ceil(cap / last[2]);
  return {
    name:`${last[0]} × ${k} 台并联`,
    range:`${last[1] * k}–${last[2] * k} kg/h`
  };
}

function fmtD97(s){
  const a = s.d97[0], b = s.d97[1];
  return `D97 ${a}–${b} µm`;
}

function render(list, ctx){
  if (!list.length){
    outEl.innerHTML = `
      <div class="card">
        <div class="empty">
          <h3>无匹配机型</h3>
          <p>当前工艺组合超出标准机型范围，<br>建议联系工程师安排物料小试后定制。</p>
        </div>
      </div>`;
    return;
  }

  const main = list[0];
  const mm = pickModel(main.s, ctx.cap);
  const matName = matEl.value.trim();

  let html = `
    <div class="res-head">评估结果 · ${ctx.sizeText}</div>
    <div class="card">
      <div class="main">
        <div class="badge">主推方案</div>
        <h2>${main.s.name}</h2>
        <p class="sub">${main.s.sub}${matName ? ' · ' + matName : ''}</p>
        <div class="grid">
          <div><span>推荐型号</span><b>${mm.name}</b></div>
          <div><span>产能范围</span><b>${mm.range}</b></div>
          <div><span>可达粒度</span><b>${fmtD97(main.s)}</b></div>
          <div><span>工艺类型</span><b>${main.s.cat}</b></div>
        </div>
        ${main.s.opt ? `<div class="opt"><b>可选配置</b><br>${main.s.opt.join(' · ')}</div>` : ''}
      </div>
    </div>`;

  const alts = list.slice(1);
  if (alts.length){
    html += `<div class="res-head">备选方案</div><div class="card">`;
    for (const a of alts){
      const am = pickModel(a.s, ctx.cap);
      html += `
        <div class="alt">
          <h3>${a.s.name}</h3>
          <p>${a.s.sub}</p>
          <div class="kv">
            <div><span>型号 </span><b>${am.name}</b></div>
            <div><span>产能 </span><b>${am.range}</b></div>
            <div><span>粒度 </span><b>${fmtD97(a.s)}</b></div>
          </div>
        </div>`;
    }
    html += `</div>`;
  }

  outEl.innerHTML = html;
}

function evaluate(){
  const sizeRaw = parseFloat(sizeEl.value);
  if (!(sizeRaw > 0)){
    outEl.innerHTML = `
      <div class="card">
        <div class="empty">
          <h3>请填写目标粒度</h3>
          <p>粒度是选型的核心参数。</p>
        </div>
      </div>`;
    return;
  }

  const capRaw = parseFloat(capEl.value);
  const cap = capRaw > 0 ? capRaw : 500;
  const d97 = normD97(sizeRaw, basis);
  const attrs = [...chipsEl.querySelectorAll('.chip.on')].map(b => b.dataset.k);

  const scored = [];
  for (const s of DB){
    const sc = scoreSeries(s, d97, cap, attrs);
    if (sc > 0) scored.push({ s, sc });
  }
  scored.sort((a, b) => b.sc - a.sc);

  render(scored.slice(0, 3), {
    cap, d97,
    sizeText: `${basis} ${sizeRaw} µm`
  });
}

$('go').addEventListener('click', evaluate);

/* 回车直接评估 */
[sizeEl, capEl].forEach(el => {
  el.addEventListener('keydown', e => {
    if (e.key === 'Enter'){ el.blur(); evaluate(); }
  });
});
</script>
</body>
</html>
