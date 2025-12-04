# Project: "Link" - Full-Stack Equipment Rental & Services Platform

**Live Site: [https://wasell.vercel.app/](https://wasell.vercel.app/)**

### Project Summary

Developed a comprehensive, full-stack web application, "Link," to serve the heavy equipment industry. The platform functions as a two-sided marketplace, enabling equipment owners to list their assets for rent and allowing contractors or clients to easily find and book them. The application also includes a service directory for specialized drivers, creating a one-stop solution for project needs. The entire platform is built on a modern, scalable architecture using Next.js and Firebase.

---

### Technical Features & Implementation Highlights

*   **Secure Role-Based Authentication:** Implemented a robust authentication system with Firebase, featuring distinct roles (Admin, Equipment Owner, Driver). User registration includes a multi-step onboarding process with server-side validation of profile data using Next.js Server Actions.

*   **Dynamic Equipment Catalog:**
    *   Built a server-rendered (SSR) public catalog for optimal performance and SEO, allowing instant loading of equipment listings.
    *   Developed an interactive management dashboard for equipment owners, using client-side components to provide a rich user experience for creating, editing, and managing listings in real-time.

*   **Advanced Image Handling:** Integrated Firebase Storage to manage uploads of high-resolution equipment and profile images. Implemented logic for handling multiple image uploads per listing.

*   **Modular & Scalable Architecture:**
    *   Leveraged the Next.js App Router to create a highly modular and maintainable codebase, with clear separation between server components, client components, and API logic.
    *   Designed a scalable Firestore database schema to efficiently query and relate data between users, equipment, and owners.

*   **Admin Control Panel:** Created a secure, restricted-access dashboard for administrators to oversee platform activity and manage users, demonstrating the ability to build complex, permission-based systems.

---

### Technology Stack

*   **Frontend:** Next.js 14 (React), TypeScript, Tailwind CSS
*   **Backend:** Next.js API Routes & Server Actions
*   **Database & Services:** Firebase (Firestore, Authentication, Cloud Storage)
*   **Deployment:** Vercel

---

### Pages Details

*   **Home (`/`):** The main landing page of the application.
*   **Privacy Policy (`/privacy-policy`):** Displays the privacy policy.
*   **Equipment Details (`/equipment/[id]`):** Shows details for a specific piece of equipment.
*   **Equipment List (`/equipment`):** Lists all available equipment.
*   **Driver Details (`/driver/[id]`):** Shows details for a specific driver.
*   **Drivers List (`/drivers`):** Lists all available drivers.

*   **Authentication (`/auth/...`):**
    *   **Login (`/auth/login`):** User login page.
    *   **Register (`/auth/register`):** User registration page.
    *   **Complete Profile (`/auth/complete-profile`):** Page for users to complete their profile information after registration.
    *   **Forgot Password (`/auth/forgot-password`):** Page to initiate password reset.
    *   **Reset Password (`/auth/reset-password`):** Page to set a new password using a reset token.
    *   **Update Password (`/auth/update-password`):** Page for logged-in users to update their password.

*   **Equipment Owner (`/equipment-owner/...`):**
    *   **Profile (`/equipment-owner/profile`):** Profile page for equipment owners.
    *   **Add Equipment (`/equipment-owner/add-equipment`):** Form for owners to add new equipment.
    *   **Edit Equipment (`/equipment-owner/edit-equipment/[id]`):** Form for owners to edit their existing equipment.

*   **Driver (`/driver/...`):**
    *   **Profile (`/driver/profile`):** Profile page for drivers.

*   **Admin (`/admin/...`):**
    *   **Dashboard (`/admin/dashboard`):** Admin dashboard for managing users and platform content.
    *   **Secret Number Management (`/admin/secret-number-management`):** Page for managing secret numbers for registration.

---
---

# مشروع: "Link" - منصة متكاملة لتأجير المعدات والخدمات

**رابط الموقع: [https://wasell.vercel.app/](https://wasell.vercel.app/)**

### ملخص المشروع

تم تطوير تطبيق ويب متكامل وشامل، "Link"، لخدمة قطاع المعدات الثقيلة. تعمل المنصة كسوق مزدوج الجوانب، حيث تمكّن أصحاب المعدات من عرض أصولهم للإيجار وتتيح للمقاولين أو العملاء العثور عليها وحجزها بسهولة. يتضمن التطبيق أيضًا دليل خدمات للسائقين المتخصصين، مما يخلق حلاً شاملاً لاحتياجات المشاريع. تم بناء المنصة بالكامل على بنية تحتية حديثة وقابلة للتطوير باستخدام Next.js و Firebase.

---

### الميزات التقنية وأبرز نقاط التنفيذ

*   **نظام مصادقة آمن قائم على الأدوار:** تم تنفيذ نظام مصادقة قوي باستخدام Firebase، مع أدوار مميزة (مدير، مالك معدات، سائق). يتضمن تسجيل المستخدم عملية إعداد متعددة الخطوات مع التحقق من صحة بيانات الملف الشخصي من جانب الخادم باستخدام Next.js Server Actions.

*   **كتالوج معدات ديناميكي:**
    *   بناء كتالوج عام مُصيّر من جانب الخادم (SSR) لتحقيق الأداء الأمثل والتوافق مع محركات البحث (SEO)، مما يسمح بالتحميل الفوري لقوائم المعدات.
    *   تطوير لوحة تحكم تفاعلية لمالكي المعدات، باستخدام مكونات من جانب العميل (client-side components) لتوفير تجربة مستخدم غنية لإنشاء وتعديل وإدارة القوائم في الوقت الفعلي.

*   **معالجة متقدمة للصور:** دمج Firebase Storage لإدارة تحميلات صور المعدات والملفات الشخصية عالية الدقة. تم تنفيذ منطق لمعالجة تحميلات صور متعددة لكل قائمة.

*   **بنية معمارية مرنة وقابلة للتطوير:**
    *   الاستفادة من Next.js App Router لإنشاء قاعدة كود قابلة للصيانة بدرجة عالية، مع فصل واضح بين مكونات الخادم ومكونات العميل ومنطق الـ API.
    *   تصميم مخطط قاعدة بيانات Firestore قابل للتطوير للاستعلام عن البيانات وربطها بكفاءة بين المستخدمين والمعدات والمالكين.

*   **لوحة تحكم للمدير:** إنشاء لوحة تحكم آمنة ومقيدة الوصول للمسؤولين للإشراف على نشاط المنصة وإدارة المستخدمين، مما يبرهن على القدرة على بناء أنظمة معقدة قائمة على الصلاحيات.

---

### المكدس التقني

*   **الواجهة الأمامية:** Next.js 14 (React), TypeScript, Tailwind CSS
*   **الخادم:** Next.js API Routes & Server Actions
*   **قاعدة البيانات والخدمات:** Firebase (Firestore, Authentication, Cloud Storage)
*   **النشر:** Vercel

---

### تفاصيل الصفحات

*   **الرئيسية (`/`):** الصفحة المقصودة الرئيسية للتطبيق.
*   **سياسة الخصوصية (`/privacy-policy`):** تعرض سياسة الخصوصية.
*   **تفاصيل المعدات (`/equipment/[id]`):** تعرض تفاصيل قطعة معينة من المعدات.
*   **قائمة المعدات (`/equipment`):** تسرد جميع المعدات المتاحة.
*   **تفاصيل السائق (`/driver/[id]`):** تعرض تفاصيل سائق معين.
*   **قائمة السائقين (`/drivers`):** تسرد جميع السائقين المتاحين.

*   **المصادقة (`/auth/...`):**
    *   **تسجيل الدخول (`/auth/login`):** صفحة تسجيل دخول المستخدم.
    *   **التسجيل (`/auth/register`):** صفحة تسجيل مستخدم جديد.
    *   **إكمال الملف الشخصي (`/auth/complete-profile`):** صفحة للمستخدمين لإكمال معلومات ملفهم الشخصي بعد التسجيل.
    *   **نسيت كلمة المرور (`/auth/forgot-password`):** صفحة لبدء عملية إعادة تعيين كلمة المرور.
    *   **إعادة تعيين كلمة المرور (`/auth/reset-password`):** صفحة لتعيين كلمة مرور جديدة باستخدام رمز إعادة التعيين.
    *   **تحديث كلمة المرور (`/auth/update-password`):** صفحة للمستخدمين المسجلين لتحديث كلمة المرور الخاصة بهم.

*   **مالك المعدات (`/equipment-owner/...`):**
    *   **الملف الشخصي (`/equipment-owner/profile`):** صفحة الملف الشخصي لأصحاب المعدات.
    *   **إضافة معدات (`/equipment-owner/add-equipment`):** نموذج للمالكين لإضافة معدات جديدة.
    *   **تعديل المعدات (`/equipment-owner/edit-equipment/[id]`):** نموذج للمالكين لتعديل معداتهم الحالية.

*   **السائق (`/driver/...`):**
    *   **الملف الشخصي (`/driver/profile`):** صفحة الملف الشخصي للسائقين.

*   **المسؤول (`/admin/...`):**
    *   **لوحة التحكم (`/admin/dashboard`):** لوحة تحكم المسؤول لإدارة المستخدمين ومحتوى المنصة.
    *   **إدارة الرقم السري (`/admin/secret-number-management`):** صفحة لإدارة الأرقام السرية للتسجيل.