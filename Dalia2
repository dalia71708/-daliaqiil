const express = require('express');
const app = express();
app.use(express.json());

app.post('/api/step1-verify', (req, res) => {
    res.json({ status: 'success', message: 'تم التحقق من الخطوة الأولى' });
});

const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
    console.log(`Server is running on port ${PORT}`);
});
