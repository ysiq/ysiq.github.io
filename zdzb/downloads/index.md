---
layout: zdzb
title: 下载中心
---

<style>
.download-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem;
}

.download-header {
    text-align: center;
    margin-bottom: 3rem;
}

.download-header h2 {
    font-size: 2rem;
    color: var(--text-primary);
    margin-bottom: 0.5rem;
}

.download-header p {
    color: var(--text-secondary);
}

.download-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
}

.download-card {
    background: var(--card-bg);
    border: 1px solid var(--border-color);
    border-radius: 12px;
    padding: 1.5rem;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.download-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
}

.download-card-icon {
    width: 48px;
    height: 48px;
    background: linear-gradient(135deg, var(--accent-green), #2d8a4e);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 1rem;
}

.download-card-icon svg {
    width: 24px;
    height: 24px;
    color: white;
}

.download-card h3 {
    font-size: 1.1rem;
    color: var(--text-primary);
    margin-bottom: 0.5rem;
}

.download-card p {
    color: var(--text-secondary);
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.download-card .file-info {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    color: var(--text-muted);
    font-size: 0.8rem;
    margin-bottom: 1rem;
}

.download-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    background: var(--accent-green);
    color: white;
    padding: 0.6rem 1.2rem;
    border-radius: 6px;
    text-decoration: none;
    font-size: 0.9rem;
    transition: background 0.3s ease;
}

.download-btn:hover {
    background: #2d8a4e;
}

.download-btn svg {
    width: 16px;
    height: 16px;
}
</style>

<div class="download-container">
    <div class="download-header">
        <h2>下载中心</h2>
        <p>获取产品说明书、技术文档等相关资料</p>
    </div>

    <div class="download-grid">
        <div class="download-card">
            <div class="download-card-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/>
                    <polyline points="14 2 14 8 20 8"/>
                    <line x1="16" y1="13" x2="8" y2="13"/>
                    <line x1="16" y1="17" x2="8" y2="17"/>
                    <polyline points="10 9 9 9 8 9"/>
                </svg>
            </div>
            <h3>灵巧手产品说明书</h3>
            <p>详细介绍灵巧手产品的机械结构、运动性能、感知系统、电气接口、安装方法及使用指南。</p>
            <div class="file-info">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M13 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9z"/>
                    <polyline points="13 2 13 9 20 9"/>
                </svg>
                <span>PDF 文档</span>
            </div>
            <a href="/zdzb/downloads/灵巧手产品说明书.pdf" download class="download-btn">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
                    <polyline points="7 10 12 15 17 10"/>
                    <line x1="12" y1="15" x2="12" y2="3"/>
                </svg>
                立即下载
            </a>
        </div>
        
        <div class="download-card">
            <div class="download-card-icon">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/>
                    <polyline points="14 2 14 8 20 8"/>
                    <line x1="16" y1="13" x2="8" y2="13"/>
                    <line x1="16" y1="17" x2="8" y2="17"/>
                    <polyline points="10 9 9 9 8 9"/>
                </svg>
            </div>
            <h3>灵巧手上位机说明书</h3>
            <p>上位机控制软件使用指南，包含软件功能介绍、操作流程、VR手套控制、状态监控等详细说明。</p>
            <div class="file-info">
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M13 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9z"/>
                    <polyline points="13 2 13 9 20 9"/>
                </svg>
                <span>Word 文档</span>
            </div>
            <a href="/zdzb/downloads/灵巧手上位机说明书.doc" download class="download-btn">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/>
                    <polyline points="7 10 12 15 17 10"/>
                    <line x1="12" y1="15" x2="12" y2="3"/>
                </svg>
                立即下载
            </a>
        </div>
    </div>
</div>
